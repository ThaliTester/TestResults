#### Test 50650278b86327b_thali05_samsung-SM-G800H Logs


```
--------- beginning of /dev/log/main
I/PCWCLIENTTRACE_PushUtil( 5070): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 5070): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5070): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_LOG( 5070): DEFAULT_LOGON : true
I/PCWCLIENTTRACE_LOG( 5070): DEFAULT_LOGLEVEL : 3
I/PCWCLIENTTRACE_SYSTEMReceiver( 5070): [onReceive] - android.intent.action.PACKAGE_ADDED
I/SELinux ( 5084): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5084):  
--------- beginning of /dev/log/system
I/ActivityManager(  759): Killing 3422:com.android.email/u0a155 (adj 15): empty #43
I/SELinux ( 5084): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5084):  
I/SELinux ( 5084):  
I/SELinux ( 5084): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5084): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5084): >>>>> Normal User
E/dalvikvm( 5084): >>>>> com.samsung.android.app.galaxyfinder [ userId:0 | appId:10034 ]
E/SELinux ( 5084): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/TimaKeyStoreProvider( 5084): in addTimaSignatureService
D/TimaKeyStoreProvider( 5084): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5084): Added TimaKesytore provider
W/System.err( 5084): java.io.FileNotFoundException: /system/finder_cp/cpdata.xml: open failed: ENOENT (No such file or directory)
W/System.err( 5084): 	at libcore.io.IoBridge.open(IoBridge.java:409)
W/System.err( 5084): 	at java.io.FileInputStream.<init>(FileInputStream.java:78)
W/System.err( 5084): 	at java.io.FileInputStream.<init>(FileInputStream.java:105)
W/System.err( 5084): 	at com.samsung.android.app.galaxyfinder.cp.CPFileLoad.loadDataFile(CPFileLoad.java:20)
W/System.err( 5084): 	at com.samsung.android.app.galaxyfinder.cp.CPDomParser.getCPData(CPDomParser.java:83)
W/System.err( 5084): 	at com.samsung.android.app.galaxyfinder.util.CategoryPreferences.getSearchCPList(CategoryPreferences.java:112)
W/System.err( 5084): 	at com.samsung.android.app.galaxyfinder.util.CategoryPreferences.updateWebCpList(CategoryPreferences.java:76)
W/System.err( 5084): 	at com.samsung.android.app.galaxyfinder.util.CategoryPreferences.init(CategoryPreferences.java:44)
W/System.err( 5084): 	at com.samsung.android.app.galaxyfinder.GalaxyFinderApplication.init(GalaxyFinderApplication.java:105)
W/System.err( 5084): 	at com.samsung.android.app.galaxyfinder.GalaxyFinderApplication.onCreate(GalaxyFinderApplication.java:89)
W/System.err( 5084): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
W/System.err( 5084): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4790)
W/System.err( 5084): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
W/System.err( 5084): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
W/System.err( 5084): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 5084): 	at android.os.Looper.loop(Looper.java:146)
W/System.err( 5084): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
W/System.err( 5084): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/System.err( 5084): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/System.err( 5084): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
W/System.err( 5084): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
W/System.err( 5084): 	at dalvik.system.NativeStart.main(Native Method)
W/System.err( 5084): Caused by: libcore.io.ErrnoException: open failed: ENOENT (No such file or directory)
W/System.err( 5084): 	at libcore.io.Posix.open(Native Method)
W/System.err( 5084): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
W/System.err( 5084): 	at libcore.io.IoBridge.open(IoBridge.java:393)
W/System.err( 5084): 	... 21 more
D/GalaxyFinderApplication( 5084): [Slink platform] Version = 29011
D/GalaxyFinderApplication( 5084): [Slink platform] use state of slink location service is [false] to [true]
I/SELinux ( 5110): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5110):  
I/ActivityManager(  759): Killing 3542:com.samsung.android.service.travel/u0a169 (adj 15): empty #43
I/SELinux ( 5110): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5110):  
I/SELinux ( 5110):  
I/SELinux ( 5110): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5110): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5110): >>>>> Normal User
E/dalvikvm( 5110): >>>>> com.policydm [ userId:0 | appId:1000 ]
E/SELinux ( 5110): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/TimaKeyStoreProvider( 5110): in addTimaSignatureService
D/TimaKeyStoreProvider( 5110): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5110): Added TimaKesytore provider
D/AndroidRuntime( 5098): 
D/AndroidRuntime( 5098): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5098): CheckJNI is OFF
D/AndroidRuntime( 5098): setted country_code = Poland
D/AndroidRuntime( 5098): setted countryiso_code = PL
D/AndroidRuntime( 5098): setted sales_code = XEO
D/AndroidRuntime( 5098): readGMSProperty: start
D/AndroidRuntime( 5098): readGMSProperty: already setted!!
D/AndroidRuntime( 5098): readGMSProperty: end
D/AndroidRuntime( 5098): addProductProperty: start
D/dalvikvm( 5098): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 5098): Added shared lib libjavacore.so 0x0
D/dalvikvm( 5098): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 5098): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 5098): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
I/SELinux ( 5134): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5134):  
I/ActivityManager(  759): Killing 3914:com.sec.android.fotaclient/u0a10 (adj 15): empty #43
D/dalvikvm(  243): GC_EXPLICIT freed 46K, 50% free 9510K/18744K, paused 2ms+2ms, total 30ms
I/SELinux ( 5134): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5134):  
I/SELinux ( 5134):  
I/SELinux ( 5134): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5134): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
E/dalvikvm( 5134): >>>>> Normal User
E/dalvikvm( 5134): >>>>> com.samsung.android.sdk.samsunglink [ userId:0 | appId:10042 ]
D/dalvikvm(  243): GC_EXPLICIT freed <1K, 50% free 9510K/18744K, paused 1ms+3ms, total 18ms
E/SELinux ( 5134): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
E/memtrack( 5098): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 5098): failed to load memtrack module: -2
D/dalvikvm(  243): GC_EXPLICIT freed <1K, 50% free 9510K/18744K, paused 1ms+2ms, total 19ms
D/TimaKeyStoreProvider( 5134): in addTimaSignatureService
D/TimaKeyStoreProvider( 5134): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5134): Added TimaKesytore provider
D/dalvikvm( 5098): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
D/AndroidRuntime( 5098): Calling main entry com.android.commands.am.Am
V/ApplicationPolicy(  759): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
D/CustomFrequencyManagerService(  759): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 759  pkgName : ACTIVITY_RESUME_BOOSTER@5
W/ActivityManager(  759): mDVFSHelper.acquire()
I/SELinux ( 5151): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5151):  
D/LockPatternUtils( 1069): isPcwEnable = null
D/AndroidRuntime( 5098): Shutting down VM
D/dalvikvm( 5098): GC_CONCURRENT freed 97K, 13% free 717K/816K, paused 1ms+1ms, total 3ms
I/SELinux ( 5151): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5151):  
I/SELinux ( 5151):  
I/SELinux ( 5151): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5151): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 5151): >>>>> Normal User
E/dalvikvm( 5151): >>>>> com.test.thalitest [ userId:0 | appId:10179 ]
E/SELinux ( 5151): [DEBUG] seapp_context_lookup: seinfoCategory = default
D/TimaKeyStoreProvider( 5151): in addTimaSignatureService
D/TimaKeyStoreProvider( 5151): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5151): Added TimaKesytore provider
D/SurfaceWidgetClient$ISurfaceWidgetStub( 1447): [237392/5] Surface widget visibility changed visibility = false on instance = 1
E/SMD     (  233): DCD ON
I/SQLiteSecureOpenHelper( 2107): getWritableDatabase(pwd)
D/LockPatternUtils( 1069): isPcwEnable = null
I/SQLiteSecureOpenHelper( 2107): getDatabaseLocked(b,b,pwd)...
I/SurfaceFlinger(  242): id=13 Removed CatteryCove (8/12)
I/SurfaceFlinger(  242): id=13 Removed CatteryCove (-2/12)
D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
D/SurfaceWidgetView( 1264): destroyHardwareResources():1126075728
I/SurfaceFlinger(  242): id=7 Removed Mauncher (7/11)
I/SurfaceFlinger(  242): id=7 Removed Mauncher (-2/11)
D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
D/Launcher( 1264): onTrimMemory. Level: 20
W/ActivityManager(  759): Permission Denial: getCurrentUser() from pid=5151, uid=10179 requires android.permission.INTERACT_ACROSS_USERS
W/ActivityManager(  759): Permission Denial: getCurrentUser() from pid=5151, uid=10179 requires android.permission.INTERACT_ACROSS_USERS
W/ActivityManager(  759): Permission Denial: getCurrentUser() from pid=5134, uid=10042 requires android.permission.INTERACT_ACROSS_USERS
V/WebViewChromium( 5151): Binding Chromium to the background looper Looper (main, tid 1) {422b7388}
I/chromium( 5151): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserProcessMain( 5151): Initializing chromium process, renderers=0
W/chromium( 5151): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
I/Adreno-EGL( 5151): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5151): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 5151): Build Date: 03/21/14 Fri
I/Adreno-EGL( 5151): Local Branch: AU200+patches_03212014
I/Adreno-EGL( 5151): Remote Branch: 
I/Adreno-EGL( 5151): Local Patches: 
I/Adreno-EGL( 5151): Reconstruct Branch: 
,E/cutils  (  220): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
W/ContextImpl( 5134): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/files
W/Vold    (  220): Returning OperationFailed - no handler for errno 30
W/ActivityManager(  759): Unable to start service Intent { cmp=com.samsung.android.sdk.samsunglink/com.sec.pcw.analytics.AnalyticsUploaderService (has extras) } U=0: not found
E/cutils  (  220): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
W/ContextImpl( 5134): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/cache
W/Vold    (  220): Returning OperationFailed - no handler for errno 30
I/SA      ( 3989): [PMR] Received action : android.intent.action.PACKAGE_ADDED
I/SA      ( 3989): [SUR] onReceive log=[SA = 2.0.0117 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = kmini3g P = kmini3gxx I = KOT49H M = SM-G800H OKLEFT false DIS KOT49H.G800HXXU1ANK2 PSS = 4.497045606779314  ]
I/SA      ( 3989): [SUR] onReceive Intent=[ action.PACKAGE_ADDED. package ]
I/dalvikvm( 5151): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 5151): VFY: unable to resolve virtual method 218: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 5151): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 5151): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 5151): VFY: unable to resolve virtual method 213: Landroid/webkit/CookieManager;.flush ()V
D/dalvikvm( 5151): VFY: replacing opcode 0x6e at 0x0008
D/Mms/PackageInstallReceiver( 4285): loadAuthorityPref(): sEnableAuthority = true
W/dalvikvm( 5151): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 5151): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 5151): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 5151): VFY: unable to resolve virtual method 271: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 5151): VFY: replacing opcode 0x6f at 0x001a
W/dalvikvm( 5151): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 5151): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 5151): VFY: unable to resolve virtual method 229: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 5151): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 5151): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 5151): VFY: unable to resolve virtual method 234: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/dalvikvm( 5151): VFY: replacing opcode 0x6e at 0x0000
D/SystemWebViewEngine( 5151): CordovaWebView is running on device made by: samsung
I/IcingCorporaProvider( 2174): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
W/ContextImpl( 4614): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:153 android.app.ActivityThread.handleReceiver:2698 
I/SELinux ( 5192): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5192):  
I/SELinux ( 5192): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5192):  
I/SELinux ( 5192):  
I/SELinux ( 5192): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5192): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
E/dalvikvm( 5192): >>>>> Normal User
I/ActivityManager(  759): Killing 3926:com.samsung.klmsagent/u0a18 (adj 15): empty #43
E/dalvikvm( 5192): >>>>> com.sec.android.service.cm [ userId:0 | appId:10078 ]
E/SELinux ( 5192): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
I/SurfaceFlinger(  242): id=16 createSurf (1x1),1 flag=404, NainActivit
D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
D/TimaKeyStoreProvider( 5192): in addTimaSignatureService
D/TimaKeyStoreProvider( 5192): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5192): Added TimaKesytore provider
D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
I/HWUI    ( 5151): EGLImpl-HWUI Protected EGL context created
D/OpenGLRenderer( 5151): Enabling debug mode 0
W/AwContents( 5151): nativeOnDraw failed; clearing to background color.
D/CapabilityManagerService New( 5192): Receiver Broadcast:android.intent.action.PACKAGE_ADDED
W/ActivityManager(  759): Permission Denial: getCurrentUser() from pid=5192, uid=10078 requires android.permission.INTERACT_ACROSS_USERS
I/IcingCorporaProvider( 2174): UpdateCorporaTask done [took 187 ms] updated apps [took 186 ms] 
D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
I/SELinux ( 5214): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5214):  
I/ActivityManager(  759): Killing 4209:com.sec.android.service.health/u0a16 (adj 15): empty #43
D/CustomFrequencyManagerService(  759): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 759  tag : ACTIVITY_RESUME_BOOSTER@5
D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
W/ActivityManager(  759): mDVFSHelper.release()
D/CustomFrequencyManagerService(  759): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 759  pkgName : ACTIVITY_RESUME_BOOSTER@9
I/SELinux ( 5214): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5214):  
I/SELinux ( 5214):  
I/SELinux ( 5214): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5214): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 5214): >>>>> Normal User
E/dalvikvm( 5214): >>>>> com.google.android.apps.docs [ userId:0 | appId:10090 ]
E/SELinux ( 5214): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
D/TimaKeyStoreProvider( 5214): in addTimaSignatureService
D/TimaKeyStoreProvider( 5214): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5214): Added TimaKesytore provider
W/ActivityManager(  759): Permission Denial: getCurrentUser() from pid=5214, uid=10090 requires android.permission.INTERACT_ACROSS_USERS
D/JsMessageQueue( 5151): Set native->JS mode to OnlineEventsBridgeMode
D/dalvikvm( 5151): Trying to load lib /data/app-lib/com.test.thalitest-31/libjxcore.so 0x425de0f8
D/dalvikvm( 5151): Added shared lib /data/app-lib/com.test.thalitest-31/libjxcore.so 0x425de0f8
D/jxcore_app_log( 5151): JniHelper::setJavaVM(0x4175b528), pthread_self() = 2033313496
D/JX-Cordova( 5151): jxcore cordova android initializing
I/dalvikvm( 5151): Could not find method android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported, referenced from method io.jxcore.node.ConnectionHelper.isBleAdvertisingSupported
W/dalvikvm( 5151): VFY: unable to resolve virtual method 52: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
D/dalvikvm( 5151): VFY: replacing opcode 0x6e at 0x0045
,I/SELinux ( 5235): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5235):  
,W/GAV2    ( 5214): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/SELinux ( 5235): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5235):  
I/SELinux ( 5235):  
,I/SELinux ( 5235): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5235): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5235): >>>>> Normal User
,E/dalvikvm( 5235): >>>>> com.samsung.android.app.watchmanagerstub [ userId:0 | appId:10100 ]
,E/SELinux ( 5235): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 5235): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5235): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5235): Added TimaKesytore provider
,D/PackageIntentReceiver( 5235): ACTION_PACKAGE_ADDED
,D/PackageIntentReceiver( 5235): Not GearManger package! 
,D/dalvikvm( 5151): GC_CONCURRENT freed 4909K, 32% free 12781K/18744K, paused 2ms+3ms, total 32ms
,D/dalvikvm( 5151): WAIT_FOR_CONCURRENT_GC blocked 22ms
,I/SELinux ( 5253): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5253):  
I/ActivityManager(  759): Killing 3939:com.sec.android.soagent/u0a37 (adj 15): empty #43
,I/SELinux ( 5253): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5253):  
I/SELinux ( 5253):  
,I/SELinux ( 5253): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5253): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 5253): >>>>> Normal User
,E/dalvikvm( 5253): >>>>> com.samsung.android.magazine.service [ userId:0 | appId:10106 ]
,E/SELinux ( 5253): [DEBUG] seapp_context_lookup: seinfoCategory = release
D/TimaKeyStoreProvider( 5253): in addTimaSignatureService
D/TimaKeyStoreProvider( 5253): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5253): Added TimaKesytore provider
,D/MagazineService Version( 5253): Magazine-Channel: 13
,D/MagazineService Version( 5253): Magazine-Provider: 13
,D/MagazineService Version( 5253): Magazine-Administrator: 11
,D/HeadlinesChannelApplication( 5253): [onCreate]
,D/MagazineService::MagazineBroadcastReceiver( 5253): [onReceive] android.intent.action.PACKAGE_ADDED com.test.thalitest
W/ActivityManager(  759): Permission Denial: getCurrentUser() from pid=5253, uid=10106 requires android.permission.INTERACT_ACROSS_USERS
,I/MagazineService::MagazineService( 5253): [onHandleIntent] ACTION_PACKAGE_INSTALLED
,I/SELinux ( 5266): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5266):  
,D/MagazineService::MagazineService( 5253): [onHandleIntent] Send broadcast to (com.test.thalitest).
I/ActivityManager(  759): Killing 1339:com.sec.android.provider.badge/u0a72 (adj 15): empty #43
,W/GAV2    ( 5214): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
I/ActivityManager(  759): Killing 4319:com.samsung.android.scloud.sync/u0a62 (adj 15): empty #43
,I/SELinux ( 5266): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5266):  
I/SELinux ( 5266):  
,I/SELinux ( 5266): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5266): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5266): >>>>> Normal User
,E/dalvikvm( 5266): >>>>> com.samsung.helphub [ userId:0 | appId:1000 ]
,E/SELinux ( 5266): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 5266): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5266): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5266): Added TimaKesytore provider
,D/CustomFrequencyManagerService(  759): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 759  tag : ACTIVITY_RESUME_BOOSTER@9
,I/SELinux ( 5280): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5280):  
I/ActivityManager(  759): Killing 4334:com.sec.android.app.clockpackage/u0a84 (adj 15): empty #43
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
,D/dalvikvm( 5151): GC_FOR_ALLOC freed 4687K, 27% free 15775K/21536K, paused 37ms, total 37ms
,W/ActivityManager(  759): Permission Denial: getCurrentUser() from pid=5280, uid=10158 requires android.permission.INTERACT_ACROSS_USERS
,D/KidsPlatformStub( 5280): Package not found : com.sec.android.app.kidshome
,I/SELinux ( 5293): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5293):  
,I/ActivityManager(  759): Killing 4346:com.sec.esdk.elm/u0a94 (adj 15): empty #43
,I/SELinux ( 5293): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5293):  
I/SELinux ( 5293):  
,I/SELinux ( 5293): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5293): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5293): >>>>> Normal User
,E/dalvikvm( 5293): >>>>> com.samsung.android.provider.shootingmodeprovider [ userId:0 | appId:10162 ]
,E/SELinux ( 5293): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 5293): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5293): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5293): Added TimaKesytore provider
,I/ActivityManager(  759): Killing 3530:com.sec.android.app.taskmanager/u0a166 (adj 15): empty #43
,D/Finsky  ( 3627): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
,D/ChimeraCfgMgr( 1761): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1761): Loading module APK com.google.android.play.games
D/PackageBroadcastService( 1761): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
I/dalvikvm( 1761): Could not find method android.app.admin.DevicePolicyManager.getProfileOwner, referenced from method com.google.android.gms.auth.WorkAccountAuthenticatorInitializer.a
W/dalvikvm( 1761): VFY: unable to resolve virtual method 174: Landroid/app/admin/DevicePolicyManager;.getProfileOwner ()Landroid/content/ComponentName;
D/dalvikvm( 1761): VFY: replacing opcode 0x6e at 0x0053
,I/dalvikvm( 1761): Failed resolving Lcom/google/android/gms/common/permission/PermissionUtils$1; interface 96 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
,W/dalvikvm( 1761): Link of class 'Lcom/google/android/gms/common/permission/PermissionUtils$1;' failed
E/dalvikvm( 1761): Could not find class 'com.google.android.gms.common.permission.PermissionUtils$1', referenced from method com.google.android.gms.chimera.GmsModuleInitializer.initializeModuleV0
W/dalvikvm( 1761): VFY: unable to resolve new-instance 2320 (Lcom/google/android/gms/common/permission/PermissionUtils$1;) in Lcom/google/android/gms/chimera/GmsModuleInitializer;
,D/dalvikvm( 1761): VFY: replacing opcode 0x22 at 0x001a
I/dalvikvm( 1761): Failed resolving Lcom/google/android/gms/common/permission/PermissionUtils$1; interface 96 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
W/dalvikvm( 1761): Link of class 'Lcom/google/android/gms/common/permission/PermissionUtils$1;' failed
,D/dalvikvm( 1761): DexOpt: unable to opt direct call 0x3207 at 0x1c in Lcom/google/android/gms/chimera/GmsModuleInitializer;.initializeModuleV0
,D/dalvikvm( 5151): GC_FOR_ALLOC freed 5056K, 31% free 16788K/24224K, paused 36ms, total 37ms
,I/dalvikvm-heap( 5151): Grow heap (frag case) to 21.783MB for 2475476-byte allocation
,D/ChimeraCfgMgr( 1761): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1761): Module APK com.google.android.play.games already loaded
,D/ChimeraCfgMgr( 1761): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/AsyncTaskServiceImpl( 1761): Submit a task: k
,D/ChimeraCfgMgr( 1761): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/ChimeraCfgMgr( 1761): Loading module com.google.android.gms.vision from APK com.google.android.gms
W/BaseAppContext( 1761): Using Auth Proxy for data requests.
,W/BaseAppContext( 1761): Using Auth Proxy for data requests.
,D/k       ( 1761): Processing package: com.test.thalitest
,D/GassUtils( 1761): Found app info for package com.test.thalitest:18. Hash: 4eebbbb84f07ed56a3e96e5e8f9d6abddaaf154fffa2a65432a1006e0fa38f32
,D/k       ( 1761): Found info for package com.test.thalitest in db.
,W/BaseAppContext( 1761): Using Auth Proxy for data requests.
,W/BaseAppContext( 1761): Using Auth Proxy for data requests.
,W/BaseAppContext( 1761): Using Auth Proxy for data requests.
,W/BaseAppContext( 1761): Using Auth Proxy for data requests.
,W/dalvikvm( 1761): VFY: unable to find class referenced in signature (Landroid/app/SharedElementCallback;)
,I/dalvikvm( 1761): Could not find method android.app.Activity.setEnterSharedElementCallback, referenced from method android.support.v4.app.w.setEnterSharedElementCallback
W/dalvikvm( 1761): VFY: unable to resolve virtual method 53: Landroid/app/Activity;.setEnterSharedElementCallback (Landroid/app/SharedElementCallback;)V
,D/dalvikvm( 1761): VFY: replacing opcode 0x6e at 0x000e
W/dalvikvm( 1761): VFY: unable to find class referenced in signature (Landroid/app/SharedElementCallback;)
I/dalvikvm( 1761): Could not find method android.app.Activity.setExitSharedElementCallback, referenced from method android.support.v4.app.w.setExitSharedElementCallback
W/dalvikvm( 1761): VFY: unable to resolve virtual method 54: Landroid/app/Activity;.setExitSharedElementCallback (Landroid/app/SharedElementCallback;)V
,D/dalvikvm( 1761): VFY: replacing opcode 0x6e at 0x000e
I/dalvikvm( 1761): Could not find method android.app.Activity.finishAfterTransition, referenced from method android.support.v4.app.w.supportFinishAfterTransition
W/dalvikvm( 1761): VFY: unable to resolve virtual method 31: Landroid/app/Activity;.finishAfterTransition ()V
D/dalvikvm( 1761): VFY: replacing opcode 0x6e at 0x0006
I/dalvikvm( 1761): Could not find method android.app.Activity.postponeEnterTransition, referenced from method android.support.v4.app.w.supportPostponeEnterTransition
W/dalvikvm( 1761): VFY: unable to resolve virtual method 49: Landroid/app/Activity;.postponeEnterTransition ()V
D/dalvikvm( 1761): VFY: replacing opcode 0x6e at 0x0006
I/dalvikvm( 1761): Could not find method android.app.Activity.startPostponedEnterTransition, referenced from method android.support.v4.app.w.supportStartPostponedEnterTransition
W/dalvikvm( 1761): VFY: unable to resolve virtual method 61: Landroid/app/Activity;.startPostponedEnterTransition ()V
,D/dalvikvm( 1761): VFY: replacing opcode 0x6e at 0x0006
,I/PeopleDatabaseHelper( 1761): cleanUpNonGplusAccounts done.
,D/dalvikvm( 5151): GC_FOR_ALLOC freed 3777K, 35% free 17476K/26644K, paused 35ms, total 35ms
,D/dalvikvm( 1308): GC_EXPLICIT freed 904K, 43% free 10789K/18744K, paused 3ms+5ms, total 37ms
,D/dalvikvm( 5151): GC_FOR_ALLOC freed 1223K, 35% free 17376K/26644K, paused 29ms, total 29ms
,D/ChimeraCfgMgr( 1761): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1761): Module APK com.google.android.play.games already loaded
,W/jxcore-log( 5151): Initializing JXcore engine
,W/jxcore-log( 5151): JXcore engine is ready
,D/AmoledAdjustTimer(  759): prevTemp = 294, currTemp = 294, prevStep = 4, currStep = 4
,W/jxcore-log( 5151): Starting JXcore engine
,E/SMD     (  233): DCD ON
,W/jxcore-log( 5151): Platform android
W/jxcore-log( 5151): 
,W/jxcore-log( 5151): Process ARCH arm
W/jxcore-log( 5151): 
,I/Icing   ( 1761): Indexing 49CA7E3A917E607C6D98AA15891295369CED2106 from com.google.android.gms
,D/dalvikvm( 1761): GC_CONCURRENT freed 1263K, 33% free 12561K/18744K, paused 4ms+9ms, total 38ms
,W/SQLiteConnectionPool( 1761): A SQLiteConnection object for database '+data+data+com_google_android_gms+databases+networkstatistics_sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,I/Icing   ( 1761): Indexing done 49CA7E3A917E607C6D98AA15891295369CED2106
,I/jxcore-log( 5151): JXcore Cordova bridge is ready!
I/jxcore-log( 5151): 
,W/jxcore-log( 5151): JXcore engine is started
,I/chromium( 5151): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,V/AlarmManager(  759): waitForAlarm result :4
,V/AlarmManager(  759): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/Headlines( 4040): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 4040): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 4040): Breath 67904 latestRequest time : 1449756651586 current time : 1449756719490
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4367, temperature: 295, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
D/BatteryService(  759): stay LED for fully charged
D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
D/UiModeManager(  759): mCoverManager.getCoverState() : true
V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1945): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
D/dalvikvm(  759): GC_EXPLICIT freed 25233K, 58% free 23815K/55576K, paused 7ms+15ms, total 196ms
D/FactoryTest( 4680): Not factory mode
D/FactoryTest( 4680): Not factory mode. isFactoryMode() returend false
D/MTPRx   ( 4680): DRIVER_TIME_OUT 60s lapsed
D/MTPRx   ( 4680): still no open session command from host, so toast
W/ContextImpl( 4680): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1398 android.content.ContextWrapper.startActivity:323 android.content.ContextWrapper.startActivity:323 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:767 android.os.Handler.dispatchMessage:102 
W/ContextImpl( 4680): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1410 android.app.ContextImpl.startActivity:1399 android.content.ContextWrapper.startActivity:323 android.content.ContextWrapper.startActivity:323 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:767 
I/VacuumService( 1220): Vacuum at: now=1449756719885 tag=VacuumService
V/ApplicationPolicy(  759): isApplicationStateBlocked userId 0 pkgname com.android.settings
D/CustomFrequencyManagerService(  759): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 759  pkgName : ACTIVITY_RESUME_BOOSTER@5
W/ActivityManager(  759): mDVFSHelper.acquire()
D/LockPatternUtils( 1069): isPcwEnable = null
I/SQLiteSecureOpenHelper( 2107): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 2107): getDatabaseLocked(b,b,pwd)...
D/LockPatternUtils( 1069): isPcwEnable = null
E/MTPRx   ( 4680): started activity for popup
E/SettingsReceiverActivity( 4680): PREF_DONT_ASK_AGAIN : false
V/AlarmManager(  759): waitForAlarm result :8
V/AlarmManager(  759): ClockReceiver onReceive() ACTION_TIME_TICK
V/AlarmManager(  759): ___SyncScheduler (v3) ACTIVATED___
V/AlarmManager(  759): <AppSync3 Whitelist>
V/AlarmManager(  759): (AppSync) ### 0 added ###
D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 1069): handleTimeUpdate
D/SettingsReceiverActivity( 4680): dev.kiessupport is : TRUE
D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
I/SurfaceFlinger(  242): id=17 createSurf (1x1),1 flag=4, TettingsRec
D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
I/Adreno-EGL( 4680): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4680): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4680): Build Date: 03/21/14 Fri
I/Adreno-EGL( 4680): Local Branch: AU200+patches_03212014
I/Adreno-EGL( 4680): Remote Branch: 
I/Adreno-EGL( 4680): Local Patches: 
I/Adreno-EGL( 4680): Reconstruct Branch: 
I/HWUI    ( 4680): EGLImpl-HWUI Protected EGL context created
D/OpenGLRenderer( 4680): Enabling debug mode 0
,I/GAV2    ( 5214): Thread[GAThread,5,main]: No campaign data found.
,E/SMD     (  233): DCD ON
,I/jxcore-log( 5151): Toggling radios to true
I/jxcore-log( 5151): 
,D/BluetoothAdapter( 5151): enable(): BT is already enabled..!
,I/WifiManager( 5151): packageName : com.test.thalitest
,I/WifiManager( 5151): setWifiEnabled : true
,I/WifiService(  759): setWifiEnabled: true pid=5151, uid=10179
,W/WifiService(  759): Failed getting userId using ActivityManagerNative
W/WifiService(  759): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=5151, uid=10179 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService(  759): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:20710)
W/WifiService(  759): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:2348)
W/WifiService(  759): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:2336)
W/WifiService(  759): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:178)
W/WifiService(  759): 	at android.os.Binder.execTransact(Binder.java:404)
W/WifiService(  759): 	at dalvik.system.NativeStart.run(Native Method)
,W/ActivityManager(  759): Permission Denial: getCurrentUser() from pid=5151, uid=10179 requires android.permission.INTERACT_ACROSS_USERS
I/WifiService(  759): disconnect: pid=5151, uid=10179
,I/jxcore-log( 5151): Radios toggled
I/jxcore-log( 5151): 
,I/wpa_supplicant( 1980): [wpa_supplicant_ctrl_iface_process] : DISCONNECT
,D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
,I/jxcore-log( 5151): Got Device Bluetooth address: 38:94:96:B5:06:DC
I/jxcore-log( 5151): 
,I/jxcore-log( 5151): Perf Test app loaded loaded
I/jxcore-log( 5151): 
,I/jxcore-log( 5151): check test folder
I/jxcore-log( 5151): 
,I/jxcore-log( 5151): found test : ./testFindPeers.js
I/jxcore-log( 5151): 
,I/wpa_supplicant( 1980): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
,I/wpa_supplicant( 1980): Prev BSS - hexdump(len=6): c0 ff d4 d3 aa 48
,I/wpa_supplicant( 1980): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
E/wpa_supplicant( 1980): Cmd 35605 not handled
,E/wpa_supplicant( 1980): Cmd 35605 not handled
D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
,D/Tethering(  759): interfaceLinkStateChanged wlan0, false
I/wpa_supplicant( 1980): P2P: updated channels: 81:1,2,3,4,5,6,7,8,9,10,11,12,13 115:36,40,44,48 116:36,44 117:40,48
,D/Tethering(  759): interfaceStatusChanged wlan0, false
D/CustomFrequencyManagerService(  759): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 759  tag : ACTIVITY_RESUME_BOOSTER@5
D/CustomFrequencyManagerService(  759): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 759  pkgName : ACTIVITY_RESUME_BOOSTER@9
D/CustomFrequencyManagerService(  759): FrequencyrequestList.getNextMaxCPUCoreRequest, index: 0
,W/ActivityManager(  759): mDVFSHelper.release()
D/Tethering(  759): InitialState.processMessage what=4
,E/Tethering(  759): No numeric data
,D/Tethering(  759): sendTetherStateChangedBroadcast 0, 0, 0
,D/NtpTrustedTime(  759): currentTimeMillis() cache hit
I/ConnectivityService(  759): defaultVal : 1, tetherEnabledInSettings : true
V/NetworkStats(  759): performPollLocked(flags=0x1)
,I/wpa_supplicant( 1980): reset timer : RESET_TIMER 0
,I/wpa_supplicant( 1980): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 1980): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
I/wpa_supplicant( 1980): First Scan Start
,I/wpa_supplicant( 1980): Scan requested (ret=0) - scan timeout 30 seconds
D/Tethering(  759): interfaceLinkStateChanged wlan0, false
,D/Tethering(  759): interfaceStatusChanged wlan0, false
,W/Settings(  759): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/WifiStateMachine(  759): ignore requestNetworkTransitionWakelock airplane:true
D/Tethering(  759): interfaceLinkStateChanged wlan0, false
,D/Tethering(  759): interfaceStatusChanged wlan0, false
D/WifiP2pService(  759): InactiveState{ what=143375 }
D/WifiP2pService(  759): P2pEnabledState{ what=143375 }
,D/CommandListener(  230): Clearing all IP addresses on wlan0
,D/NtpTrustedTime(  759): currentTimeMillis() cache hit
D/STATUSBAR-NetworkController_dual( 1069): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews set mobileLabel[SIM_0] =
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 set mobileLabel[SIM_1] =
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set as slot1`s
,V/NetworkStats(  759): performPollLocked() took 33ms
D/NtpTrustedTime(  759): currentTimeMillis() cache hit
D/NtpTrustedTime(  759): currentTimeMillis() cache hit
I/jxcore-log( 5151): found test : ./testSendData.js
I/jxcore-log( 5151): 
,I/WifiTrafficPoller(  759): evaluateTrafficStatsPolling
D/ConnectivityService(  759): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
D/ConnectivityService(  759): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
D/STATUSBAR-NetworkController_dual( 1069): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
E/ConnectivityService(  759): net.tcp.usercfg.default not found in system default properties
E/ConnectivityService(  759): Can't set delayed ACK size:java.io.FileNotFoundException: /sys/kernel/ipv4/tcp_use_userconfig: open failed: ENOENT (No such file or directory)
E/ConnectivityService(  759): net.tcp.delack.default not found in system default properties
D/SignalClusterView_dual( 1069): wifi: VISIBLE sig=2130837979 act=2130837934
D/SignalClusterView_dual( 1069): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1069): apply() mSeparateMobileGroup=8
D/STATUSBAR-NetworkController_dual( 1069): refreshSignalCluster - setNWBoosterIndicators(false)
D/SignalClusterView_dual( 1069): wifi: GONE sig=2130837981 act=2130837934
D/SignalClusterView_dual( 1069): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1069): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1069): wifi: GONE sig=2130837981 act=2130837934
D/SignalClusterView_dual( 1069): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1069): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1069): wifi: GONE sig=2130837981 act=2130837934
D/SignalClusterView_dual( 1069): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1069): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1069): wifi: GONE sig=2130837981 act=2130837934
D/SignalClusterView_dual( 1069): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1069): apply() mSeparateMobileGroup=8
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set : simMode = 0
E/ConnectivityService(  759): Can't set delayed ACK size:java.io.FileNotFoundException: /sys/kernel/ipv4/tcp_delack_seg: open failed: ENOENT (No such file or directory)
D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set as slot1`s
D/ConnectivityService(  759): Attempting to switch to mobile
D/ConnectivityService(  759): Attempting to switch to BLUETOOTH_TETHER
,I/wpa_supplicant( 1980): wlan0: Setting scan request: 0 sec 0 usec
,I/wpa_supplicant( 1980): Skip scan - already scanning
I/SELinux ( 5360): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5360):  
D/STATUSBAR-IconMerger( 1069): checkOverflow(336), More:false, Req:false Child:2
,V/RouteController(  230): /system/bin/ip -6 route del default table 2 2>&1
,D/WifiP2pService(  759): InactiveState{ what=143375 }
,D/WifiP2pService(  759): P2pEnabledState{ what=143375 }
,D/STATUSBAR-NetworkController_dual( 1069): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set : simMode = 0
,V/RouteController(  230): RTNETLINK answers: No such process
,V/RouteController(  230): /system/bin/ip -6 rule del table 2 2>&1
D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set as slot1`s
,I/SELinux ( 5360): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5360):  
I/SELinux ( 5360):  
,I/SELinux ( 5360): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5360): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 5360): >>>>> Normal User
,E/dalvikvm( 5360): >>>>> com.vlingo.midas [ userId:0 | appId:10033 ]
,E/SELinux ( 5360): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,V/RouteController(  230): RTNETLINK answers: No such file or directory
,D/CommandListener(  230): Clearing all IP addresses on wlan0
,W/NetworkManagementService(  759): route cmd failed: 
W/NetworkManagementService(  759): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '37 route del src v6 2' failed with '400 37 -6 rule del table 2: RTNETLINK answers: No such file or directory
W/NetworkManagementService(  759): '
W/NetworkManagementService(  759): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:406)
W/NetworkManagementService(  759): 	at com.android.server.NativeDaemonConnector.executeForList(NativeDaemonConnector.java:338)
W/NetworkManagementService(  759): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:303)
W/NetworkManagementService(  759): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:288)
W/NetworkManagementService(  759): 	at com.android.server.NetworkManagementService.delSrcRoute(NetworkManagementService.java:2502)
W/NetworkManagementService(  759): 	at com.android.server.ConnectivityService.updateSourceRoutes(ConnectivityService.java:4156)
W/NetworkManagementService(  759): 	at com.android.server.ConnectivityService.handleConnectivityChange(ConnectivityService.java:3938)
W/NetworkManagementService(  759): 	at com.android.server.ConnectivityService.handleDisconnect(ConnectivityService.java:3088)
W/NetworkManagementService(  759): 	at com.android.server.ConnectivityService.access$1800(ConnectivityService.java:258)
W/NetworkManagementService(  759): 	at com.android.server.ConnectivityService$NetworkStateTrackerHandler.handleMessage(ConnectivityService.java:4781)
W/NetworkManagementService(  759): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/NetworkManagementService(  759): 	at android.os.Looper.loop(Looper.java:146)
W/NetworkManagementService(  759): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,V/RouteController(  230): /system/bin/ip -4 route del default table 2 2>&1
,I/WifiTrafficPoller(  759): evaluateTrafficStatsPolling
D/STATUSBAR-NetworkController_dual( 1069): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set as slot1`s
,E/WifiStateMachine(  759): Error! unhandled message{ when=-98ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
,E/WifiStateMachine(  759): Error! unhandled message{ when=-97ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
,V/RouteController(  230): RTNETLINK answers: No such process
,E/WifiStateMachine(  759): Error! unhandled message{ when=-6ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
,V/RouteController(  230): /system/bin/ip -4 rule del table 2 2>&1
,D/TimaKeyStoreProvider( 5360): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5360): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5360): Added TimaKesytore provider
,V/RouteController(  230): /system/bin/ip route flush cached 2>&1
,D/NetUtils(  759): android_net_utils_resetConnections in env=0x78123f60 clazz=0x6be00001 iface=wlan0 mask=0x3
D/ConnectivityService(  759): resetConnections(wlan0, 3)
,I/chromium( 5151): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,V/NativeCrypto( 1308): Read error: ssl=0x7c5127d8: I/O error during system call, Connection timed out
,V/NativeCrypto( 1308): SSL shutdown failed: ssl=0x7c5127d8: I/O error during system call, Broken pipe
,I/System.out( 5360): Inside WakeupProvider
,I/System.out( 5360): Inside onCreate() of WakeupTriggerProvide
,D/NtpTrustedTime(  759): currentTimeMillis() cache hit
,D/NtpTrustedTime(  759): currentTimeMillis() cache hit
,D/NtpTrustedTime(  759): currentTimeMillis() cache hit
D/NtpTrustedTime(  759): currentTimeMillis() cache hit
,D/NtpTrustedTime(  759): currentTimeMillis() cache hit
V/NetworkStats(  759): updateIfacesLocked()
V/NetworkStats(  759): performPollLocked(flags=0x1)
D/ConnectivityService(  759): handleInetConditionChange: no active default network - ignore
V/NetworkStats(  759): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,D/NtpTrustedTime(  759): currentTimeMillis() cache hit
V/NetworkStats(  759): performPollLocked() took 17ms
,D/NtpTrustedTime(  759): currentTimeMillis() cache hit
,D/NtpTrustedTime(  759): currentTimeMillis() cache hit
,I/VlingoApplication( 5360): VlingoApplication appVersion ='11.4.0.3.34005', ro.csc.sales_code=XEO
,D/VlingoApplication( 5360): Couldn't create com.nuance.nuancedebugutilpackage context for host settings utility
,D/VlingoApplication( 5360): Couldn't create com.vlingo.midas.lmttutilitypackage context for host settings utility
,D/NearbySettings( 1312): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1312): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1312): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,I/NearbySettings( 1312): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1312): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1312): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 1312): MountReceiver.mPrefHandler - 7002
,D/DialogFlow( 5360): initQueue()
,D/NearbySettings( 1312): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1312): DMSUtil.isNetworkConnected - flag-null, state-null
I/NearbySettings( 1312): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
I/NearbySettings( 1312): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1312): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1312): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 1312): MountReceiver.mPrefHandler - 7002
I/ActivityManager(  759): Killing 4373:com.qualcomm.timeservice/u0a168 (adj 15): empty #43
,I/ApplicationPolicy(  759): updateDataUsageMap
,D/Tethering(  759): Tethering got CONNECTIVITY_ACTION
,D/Tethering(  759): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  759): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  759): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
D/STATUSBAR-NetworkController_dual( 1069): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set as slot1`s
,D/accuweather( 1447): [KK AccuPhone]>>> SWW:64 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/LocSvc_java(  759): updateNetworkState unavailable info: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/LocSvc_java(  759): getAGpsConnectionInfo connType - 4
,D/LocSvc_java(  759): ignore wifi update if we are not in OPENING or CLOSING
,I/NetworkMonitor( 3855): type=WIFI subType= reason=null isConnected=false
,I/PCWCLIENTTRACE_PushUtil( 5070): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 5070): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5070): getPushTypeList : [SPP, GCM]
,I/PCWCLIENTTRACE_SYSTEMReceiver( 5070): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/PCWCLIENTTRACE_SYSTEMReceiver( 5070): noConnectivity : true
,I/SELinux ( 5394): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5394):  
,I/SELinux ( 5394): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5394):  
I/SELinux ( 5394):  
,I/SELinux ( 5394): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5394): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5394): >>>>> Normal User
,E/dalvikvm( 5394): >>>>> com.sec.android.cloudagent [ userId:0 | appId:10002 ]
,E/SELinux ( 5394): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 5394): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5394): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5394): Added TimaKesytore provider
,D/CustomFrequencyManagerService(  759): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 759  tag : ACTIVITY_RESUME_BOOSTER@9
,W/ActivityManager(  759): Permission Denial: getCurrentUser() from pid=5394, uid=10002 requires android.permission.INTERACT_ACROSS_USERS
,I/ActivityManager(  759): Killing 4388:com.sec.android.app.sns3/u0a36 (adj 15): empty #43
,I/wpa_supplicant( 1980): nl80211: Received scan results (11 BSSes)
,I/wpa_supplicant( 1980): wlan0: Setting scan request: 8 sec 0 usec
I/wpa_supplicant( 1980): Trying to associate with SSID '4E47373030'
I/wpa_supplicant( 1980): Trying to associate with  'G700'
I/wpa_supplicant( 1980): Re-associate with C0.AA.48
,I/wpa_supplicant( 1980): CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00.00.00 SSID=
,E/wpa_supplicant( 1980): Cmd 35609 not handled
,D/Tethering(  759): interfaceLinkStateChanged wlan0, false
,D/Tethering(  759): interfaceStatusChanged wlan0, false
,I/SELinux ( 5417): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5417):  
,D/dalvikvm(  243): GC_EXPLICIT freed 43K, 50% free 9510K/18744K, paused 3ms+3ms, total 27ms
,D/dalvikvm(  243): GC_EXPLICIT freed <1K, 50% free 9510K/18744K, paused 2ms+2ms, total 20ms
,I/SELinux ( 5417): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5417):  
I/SELinux ( 5417):  
,I/SELinux ( 5417): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5417): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 5417): >>>>> Normal User
,E/dalvikvm( 5417): >>>>> com.sec.android.fotaclient [ userId:0 | appId:10010 ]
,E/SELinux ( 5417): [DEBUG] seapp_context_lookup: seinfoCategory = release
,E/wpa_supplicant( 1980): Cmd 35605 not handled
E/wpa_supplicant( 1980): Cmd 35847 not handled
E/wpa_supplicant( 1980): Cmd 35848 not handled
,E/wpa_supplicant( 1980): Cmd 35605 not handled
I/wpa_supplicant( 1980): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
I/wpa_supplicant( 1980): Associated with C0.AA.48
I/wpa_supplicant( 1980): freq(2412) increment count 2
,I/wpa_supplicant( 1980): meet head of list.
,I/wpa_supplicant( 1980): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
,D/dalvikvm(  243): GC_EXPLICIT freed <1K, 50% free 9510K/18744K, paused 2ms+3ms, total 23ms
D/Tethering(  759): interfaceLinkStateChanged wlan0, false
,D/Tethering(  759): interfaceStatusChanged wlan0, false
D/Tethering(  759): interfaceLinkStateChanged wlan0, false
I/wpa_supplicant( 1980): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
,D/Tethering(  759): interfaceStatusChanged wlan0, false
I/wpa_supplicant( 1980): WPA: Key negotiation completed with C0.AA.48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 1980): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
,I/wpa_supplicant( 1980): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
D/Tethering(  759): interfaceLinkStateChanged wlan0, false
,D/Tethering(  759): interfaceStatusChanged wlan0, false
,D/WifiNative(  759): callSECApiVoid - ID [50]
D/Tethering(  759): interfaceLinkStateChanged wlan0, true
,D/Tethering(  759): interfaceStatusChanged wlan0, true
,E/Tethering(  759): No numeric data
,D/Tethering(  759): sendTetherStateChangedBroadcast 1, 0, 0
I/ConnectivityService(  759): defaultVal : 1, tetherEnabledInSettings : true
,D/NtpTrustedTime(  759): currentTimeMillis() cache hit
,D/TimaKeyStoreProvider( 5417): in addTimaSignatureService
V/NetworkStats(  759): performPollLocked(flags=0x1)
,D/STATUSBAR-NetworkController_dual( 1069): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
,D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set : simMode = 0
,D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set as slot1`s
D/TimaKeyStoreProvider( 5417): Cannot add TimaSignature Service, License check Failed
D/Tethering(  759): interfaceLinkStateChanged wlan0, true
D/Tethering(  759): interfaceStatusChanged wlan0, true
D/ActivityThread( 5417): Added TimaKesytore provider
,D/Tethering(  759): interfaceLinkStateChanged wlan0, true
,D/Tethering(  759): interfaceStatusChanged wlan0, true
,D/Tethering(  759): interfaceLinkStateChanged wlan0, true
,D/Tethering(  759): interfaceStatusChanged wlan0, true
D/Tethering(  759): interfaceLinkStateChanged wlan0, true
,D/Tethering(  759): interfaceStatusChanged wlan0, true
,D/NtpTrustedTime(  759): currentTimeMillis() cache hit
D/NtpTrustedTime(  759): currentTimeMillis() cache hit
,D/NtpTrustedTime(  759): currentTimeMillis() cache hit
D/WifiP2pService(  759): InactiveState{ what=143375 }
D/WifiP2pService(  759): P2pEnabledState{ what=143375 }
V/NetworkStats(  759): performPollLocked() took 42ms
,W/ActivityManager(  759): Permission Denial: getCurrentUser() from pid=5417, uid=10010 requires android.permission.INTERACT_ACROSS_USERS
,I/ActivityManager(  759): Killing 4410:com.sec.spp.push:RemoteDlcProcess/u0a38 (adj 15): empty #43
,I/SELinux ( 5430): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5430):  
,I/SELinux ( 5430): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5430):  
I/SELinux ( 5430):  
,I/SELinux ( 5430): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5430): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5430): >>>>> Normal User
,E/dalvikvm( 5430): >>>>> com.samsung.klmsagent [ userId:0 | appId:10018 ]
,E/SELinux ( 5430): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 5430): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5430): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5430): Added TimaKesytore provider
,W/ActivityManager(  759): Permission Denial: getCurrentUser() from pid=5430, uid=10018 requires android.permission.INTERACT_ACROSS_USERS
,D/KLMS-2.3.201 : ( 5430): KLMSValidator() : checkQATesting()
,I/KLMS-2.3.201 : ( 5430): MainReciver() : EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1449756721879
,I/KLMS-2.3.201 : ( 5430): KLMSUtility() : isNetworkAvailable() - WIFI : false| MOBILE : false
,I/dhcpcd  ( 5442): if(wlan0) info get Success. (MAC : C0.AA.48)
,I/dhcpcd  ( 5442): bssid match
I/ActivityManager(  759): Killing 4427:com.sec.spp.push:RemoteNotiProcess/u0a38 (adj 15): empty #43
,I/SELinux ( 5449): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5449):  
,I/SELinux ( 5449): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5449):  
I/SELinux ( 5449):  
,I/SELinux ( 5449): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5449): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 5449): >>>>> Normal User
,E/dalvikvm( 5449): >>>>> com.sec.android.soagent [ userId:0 | appId:10037 ]
,E/SELinux ( 5449): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/TimaKeyStoreProvider( 5449): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5449): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5449): Added TimaKesytore provider
,W/ActivityManager(  759): Permission Denial: getCurrentUser() from pid=5449, uid=10037 requires android.permission.INTERACT_ACROSS_USERS
D/SO_AGENT( 5449): [AccRegisterReceiver.java(Line:56/Method:onReceive)] Receive broadcast meassage:android.net.conn.CONNECTIVITY_CHANGE
I/SO_AGENT( 5449): [AccRegisterReceiver.java(Line:80/Method:onReceive)] Network is not available
,I/SA      ( 3989): [OR] onReceive log=[SA = 2.0.0117 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = kmini3g P = kmini3gxx I = KOT49H M = SM-G800H OKLEFT false DIS KOT49H.G800HXXU1ANK2 PSS = 4.497045606779314  ]
,I/SA      ( 3989): [BDLM] already registered in spp
I/SA      ( 3989): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. ]
,I/SA      ( 3989): [OR] == ACTION_CONNECTIVITY_CHANGE ==
I/SA      ( 3989): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 3989): [OR] == isSIMCardReady false ==
I/SA      ( 3989): [SCU] == networkStateCheck == false
,I/SA      ( 3989): [OR] onReceive END
I/ActivityManager(  759): Killing 4547:com.sec.android.app.videoplayer/u0a52 (adj 15): empty #43
,D/PhoneNumberLocatorBootCompletedReceiver( 1241): onReceive
,D/PhoneNumberLocatorBootCompletedReceiver( 1241): Phone number locator feature is dsiabled
,I/SELinux ( 5461): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5461):  
,I/SELinux ( 5461): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5461):  
I/SELinux ( 5461):  
,I/SELinux ( 5461): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5461): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5461): >>>>> Normal User
,E/dalvikvm( 5461): >>>>> com.samsung.android.scloud.backup [ userId:0 | appId:10060 ]
,E/SELinux ( 5461): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 5461): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5461): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5461): Added TimaKesytore provider
,I/sCloudBackupApp( 5461): sCloudBackupApp Version Info : 3.7.3.KK_APP
,I/SCloudBackupReceiver( 5461): Other Intent
,D/com.samsung.app( 1447): [KK_EASY_Accu]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/com.samsung.app( 1447): [KK_EASY_Accu]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
I/ActivityManager(  759): Killing 4571:com.sec.android.app.voicenote/1000 (adj 15): empty #43
,I/SELinux ( 5478): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5478):  
,I/SELinux ( 5478): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5478):  
I/SELinux ( 5478):  
,I/SELinux ( 5478): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5478): [DEBUG] seapp_context_lookup: seinfoCategory = chrome
E/dalvikvm( 5478): >>>>> Normal User
,E/dalvikvm( 5478): >>>>> com.android.chrome [ userId:0 | appId:10081 ]
,E/SELinux ( 5478): [DEBUG] seapp_context_lookup: seinfoCategory = chrome
,D/TimaKeyStoreProvider( 5478): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5478): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5478): Added TimaKesytore provider
,W/ActivityManager(  759): Permission Denial: getCurrentUser() from pid=5478, uid=10081 requires android.permission.INTERACT_ACROSS_USERS
,I/ActivityManager(  759): Killing 4576:com.android.providers.calendar/u0a44 (adj 15): empty #43
,D/Headlines( 4040): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 4040): getCountryCode(): countryCode = PL
D/Headlines( 4040): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
D/HeadlinesCardManager( 4040): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 4040): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 4040): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 4040): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 4040): requestUpdateNewsWelcomeCard : request update welcome card to content card.
,D/HeadlinesDataCenter( 4040): requestUpdateNewsWelcomeCard !!! no welcome card
,I/SELinux ( 5491): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5491):  
,I/SELinux ( 5491): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5491):  
I/SELinux ( 5491):  
,I/SELinux ( 5491): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5491): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 5491): >>>>> Normal User
,E/dalvikvm( 5491): >>>>> com.google.android.apps.magazines [ userId:0 | appId:10112 ]
,E/SELinux ( 5491): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 5491): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5491): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5491): Added TimaKesytore provider
,E/cutils  (  220): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/ContextImpl( 5491): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
W/Vold    (  220): Returning OperationFailed - no handler for errno 30
,E/cutils  (  220): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/ContextImpl( 5491): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
W/Vold    (  220): Returning OperationFailed - no handler for errno 30
,E/cutils  (  220): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/ContextImpl( 5491): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,W/GAV2    ( 5491): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
W/Vold    (  220): Returning OperationFailed - no handler for errno 30
,E/cutils  (  220): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/ContextImpl( 5491): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
W/Vold    (  220): Returning OperationFailed - no handler for errno 30
,V/WebViewChromium( 5491): Binding Chromium to the main looper Looper (main, tid 1) {422bb000}
,I/chromium( 5491): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserProcessMain( 5491): Initializing chromium process, renderers=0
,W/chromium( 5491): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
,I/Adreno-EGL( 5491): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5491): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 5491): Build Date: 03/21/14 Fri
I/Adreno-EGL( 5491): Local Branch: AU200+patches_03212014
I/Adreno-EGL( 5491): Remote Branch: 
I/Adreno-EGL( 5491): Local Patches: 
I/Adreno-EGL( 5491): Reconstruct Branch: 
,I/NSApplication( 5491): Starting up...
,W/ActivityManager(  759): Permission Denial: getCurrentUser() from pid=5491, uid=10112 requires android.permission.INTERACT_ACROSS_USERS
,I/ActivityManager(  759): Killing 4630:com.google.android.talk/u0a105 (adj 15): empty #43
,D/QuickConnect[1.1][2] ( 3311): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect[1.1][2] ( 3311): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,V/QuickConnect[1.1][2] ( 3311): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@425ed340
,I/SELinux ( 5530): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5530):  
,I/SELinux ( 5530): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5530):  
I/SELinux ( 5530):  
,I/SELinux ( 5530): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5530): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5530): >>>>> Normal User
,E/dalvikvm( 5530): >>>>> com.android.email [ userId:0 | appId:10155 ]
,E/SELinux ( 5530): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 5530): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5530): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5530): Added TimaKesytore provider
,D/SSRMv2:SIOP(  759): SIOP:: AP = 330, Delta = 20
,D/RCPManagerService(  759): exchangeData() failure , invalid userId
,D/RCPManagerService(  759): exchangeData() failure , invalid userId
,D/RCPManagerService(  759): exchangeData() failure , invalid userId
,D/RCPManagerService(  759): exchangeData() failure , invalid userId
,D/RCPManagerService(  759): exchangeData() failure , invalid userId
,D/RCPManagerService(  759): exchangeData() failure , invalid userId
,I/SELinux ( 5558): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5558):  
,I/ActivityManager(  759): Killing 3007:com.sec.android.app.FileShareServer/u0a69 (adj 15): empty #43
,I/SELinux ( 5565): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5565):  
W/ActivityManager(  759): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,I/SELinux ( 5558): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5558):  
I/SELinux ( 5558):  
,I/SELinux ( 5558): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5558): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 5558): >>>>> Normal User
,E/dalvikvm( 5558): >>>>> com.sec.android.provider.badge [ userId:0 | appId:10072 ]
,E/SELinux ( 5558): [DEBUG] seapp_context_lookup: seinfoCategory = release
,E/SMD     (  233): DCD ON
,D/TimaKeyStoreProvider( 5558): in addTimaSignatureService
I/SELinux ( 5565): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5565):  
I/SELinux ( 5565):  
,I/SELinux ( 5565): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5565): [DEBUG] seapp_context_lookup: seinfoCategory = shared
E/dalvikvm( 5565): >>>>> Normal User
,E/dalvikvm( 5565): >>>>> com.samsung.android.service.travel [ userId:0 | appId:10169 ]
,E/SELinux ( 5565): [DEBUG] seapp_context_lookup: seinfoCategory = shared
,D/TimaKeyStoreProvider( 5558): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5558): Added TimaKesytore provider
,I/ActivityManager(  759): Killing 4705:com.sec.knox.bridge/1000 (adj 15): empty #43
,D/TimaKeyStoreProvider( 5565): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5565): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5565): Added TimaKesytore provider
,D/BadgeProvider( 5558): onCreate
,D/BadgeProvider( 5558): DatabaseHelper
,W/ActivityManager(  759): Permission Denial: getCurrentUser() from pid=5558, uid=10072 requires android.permission.INTERACT_ACROSS_USERS
,D/BadgeProvider( 5558): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
W/ActivityManager(  759): Permission Denial: getCurrentUser() from pid=5565, uid=10169 requires android.permission.INTERACT_ACROSS_USERS
,D/BadgeProvider( 5558): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 5558): sendNotify, [notify] : null
D/BadgeProvider( 5558): update, [uri] : content://com.sec.badge/apps/1
,D/BadgeProvider( 5558): update, [BadgeCount] : badgecount=0
,D/BadgeProvider( 5558): update, [UpdateCount] : 1
,D/Launcher.Model( 1264): reloadBadges entered.
,I/iu.Environment( 1761): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 1761): num queued entries: 0
,I/iu.UploadsManager( 1761): num updated entries: 0
,I/iu.SyncManager( 1761): NEXT; no task
I/ActivityManager(  759): Killing 4725:com.wssyncmldm/1000 (adj 15): empty #43
D/WifiP2pService(  759): InactiveState{ what=143375 }
D/WifiP2pService(  759): P2pEnabledState{ what=143375 }
,D/NearbySettings( 1312): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1312): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1312): DMSUtil.isNetworkConnected - WIFI: OBTAINING_IPADDR
,I/NearbySettings( 1312): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1312): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 1312): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 1312): MountReceiver.mPrefHandler - 7002
,D/WifiStateMachine(  759): VerifyingLinkState enter
D/STATUSBAR-NetworkController_dual( 1069): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set as slot1`s
D/STATUSBAR-NetworkController_dual( 1069): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set : simMode = 0
,D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set as slot1`s
D/WifiStateMachine(  759): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
D/WifiStateMachine(  759): CaptivePortalCheckState enter
,I/WifiTrafficPoller(  759): evaluateTrafficStatsPolling
,D/WifiStateMachine(  759): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
D/ConnectivityService(  759): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  759): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/STATUSBAR-NetworkController_dual( 1069): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set as slot1`s
,I/WifiTrafficPoller(  759): evaluateTrafficStatsPolling
I/WifiTrafficPoller(  759): mBoosterFLAG : 2
,I/WifiTrafficPoller(  759): current booster mode : BTCoexMode
D/ConnectivityService(  759): ConnectivityChange for WIFI: CONNECTED/CONNECTED
D/STATUSBAR-NetworkController_dual( 1069): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/SignalClusterView_dual( 1069): wifi: GONE sig=2130837981 act=2130837934
D/SignalClusterView_dual( 1069): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1069): apply() mSeparateMobileGroup=8
D/STATUSBAR-NetworkController_dual( 1069): refreshSignalCluster - setNWBoosterIndicators(false)
E/ConnectivityService(  759): net.tcp.usercfg.wifi not found in system properties. Using defaults
E/ConnectivityService(  759): net.tcp.delack.wifi not found in system properties. Using defaults
D/SignalClusterView_dual( 1069): wifi: VISIBLE sig=2130837979 act=2130837934
D/SignalClusterView_dual( 1069): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1069): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1069): wifi: VISIBLE sig=2130837979 act=2130837934
D/SignalClusterView_dual( 1069): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1069): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1069): wifi: VISIBLE sig=2130837979 act=2130837934
D/SignalClusterView_dual( 1069): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1069): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1069): wifi: VISIBLE sig=2130837979 act=2130837934
D/SignalClusterView_dual( 1069): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1069): apply() mSeparateMobileGroup=8
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews set mobileLabel[SIM_0] =
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 set mobileLabel[SIM_1] =
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set as slot1`s
,D/NearbySettings( 1312): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1312): MountReceiver.onReceive - Keep current state
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,D/NearbySettings( 1312): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1312): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1312): DMSUtil.isNetworkConnected - WIFI: CONNECTED
I/NearbySettings( 1312): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1312): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 1312): MountReceiver.onReceive - Keep current state
,D/ConnectivityService(  759): handleConnectivityChange: setting default proxy info 
,V/RouteController(  230): /system/bin/ip -4 route replace default via 192.168.1.1 dev wlan0 scope global table 2 2>&1
,V/RouteController(  230): /system/bin/ip -4 rule del table 2 2>&1
,D/Toast   ( 1312):  checkMirrorLinkEnabled returns : false
,D/Toast   ( 1312): showing allowed
,V/RouteController(  230): RTNETLINK answers: No such file or directory
,D/NearbySettings( 1312): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/RouteController(  230): /system/bin/ip -4 rule add from 192.168.1.143 lookup 2 prio 150 2>&1
,I/NearbySettings( 1312): MountReceiver.onReceive - Keep current state
,I/SurfaceFlinger(  242): id=18 createSurf (1x1),1 flag=4, Uoast
,V/RouteController(  230): /system/bin/ip route flush cached 2>&1
,D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
,V/RouteController(  230): /system/bin/ip route del 192.168.1.0/24 table 2 2>&1
,V/RouteController(  230): RTNETLINK answers: No such process
,V/RouteController(  230): /system/bin/ip route add 192.168.1.0/24 dev wlan0 table 2 metric 0 2>&1
,D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
D/PowerManagerService(  759): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=759
,D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
,V/RouteController(  230): /system/bin/ip route flush cached 2>&1
,D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
,D/NtpTrustedTime(  759): currentTimeMillis() cache hit
,D/NtpTrustedTime(  759): currentTimeMillis() cache hit
,D/NtpTrustedTime(  759): currentTimeMillis() cache hit
,D/NtpTrustedTime(  759): currentTimeMillis() cache hit
,D/NtpTrustedTime(  759): currentTimeMillis() cache hit
V/NetworkStats(  759): updateIfacesLocked()
V/NetworkStats(  759): performPollLocked(flags=0x1)
V/NetworkStats(  759): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,D/NtpTrustedTime(  759): currentTimeMillis() cache hit
V/NetworkStats(  759): performPollLocked() took 17ms
,D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
,D/NtpTrustedTime(  759): currentTimeMillis() cache hit
,D/NtpTrustedTime(  759): currentTimeMillis() cache hit
,D/Tethering(  759): Tethering got CONNECTIVITY_ACTION
,D/Tethering(  759): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  759): NoActiveNetworkState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
D/STATUSBAR-NetworkController_dual( 1069): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews set mobileLabel[SIM_0] =
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 set mobileLabel[SIM_1] =
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set as slot1`s
,D/accuweather( 1447): [KK AccuPhone]>>> SWW:64 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/LocSvc_java(  759): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/LocSvc_java(  759): getAGpsConnectionInfo connType - 4
,D/LocSvc_java(  759): ignore wifi update if we are not in OPENING or CLOSING
,I/NetworkMonitor( 3855): type=WIFI subType= reason=null isConnected=true
,I/PCWCLIENTTRACE_PushUtil( 5070): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 5070): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5070): getPushTypeList : [SPP, GCM]
,I/PCWCLIENTTRACE_SYSTEMReceiver( 5070): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/KLMS-2.3.201 : ( 5430): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.3.201 : ( 5430): MainReciver() : EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1449756724373
,I/KLMS-2.3.201 : ( 5430): KLMSUtility() : isNetworkAvailable() - WIFI : true| MOBILE : false
,I/LocationTagReadyService( 2559): onStartCommand : Action = com.samsung.android.app.galaxyfinder.tag.start_location_convert
,D/SO_AGENT( 5449): [AccRegisterReceiver.java(Line:56/Method:onReceive)] Receive broadcast meassage:android.net.conn.CONNECTIVITY_CHANGE
D/GalaxyFinderApplication( 2559): [Slink platform] The state of Slink geocode service is true
,D/GalaxyFinderApplication( 2559): [Slink platform] The state of Slink geocode service is true
,D/GalaxyFinderApplication( 2559): [Slink platform] The state of Slink geocode service is true
,I/SO_AGENT( 5449): [AccRegisterReceiver.java(Line:87/Method:onReceive)] Need to accessory setup...
,I/SELinux ( 5631): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5631):  
,I/GallerySearchProvider( 2403): query content://com.sec.android.gallery3d.provider.GallerySearchProvider/search_suggest_tag_query
,I/SELinux ( 5631): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5631):  
I/SELinux ( 5631):  
,I/SELinux ( 5631): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5631): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5631): >>>>> Normal User
E/dalvikvm( 5631): >>>>> com.sec.android.app.videoplayer [ userId:0 | appId:10052 ]
,E/SELinux ( 5631): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 5631): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5631): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5631): Added TimaKesytore provider
,I/SELinux ( 5643): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5643):  
,I/SA      ( 3989): [OR] onReceive log=[SA = 2.0.0117 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = kmini3g P = kmini3gxx I = KOT49H M = SM-G800H OKLEFT false DIS KOT49H.G800HXXU1ANK2 PSS = 4.497045606779314  ]
,I/SA      ( 3989): [BDLM] already registered in spp
,I/SA      ( 3989): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. ]
,I/SA      ( 3989): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      ( 3989): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 3989): [OR] == isSIMCardReady false ==
,I/SA      ( 3989): [SCU] == networkStateCheck == true
I/SA      ( 3989): [DM] getCountryCodeFromCSC : PL
I/SA      ( 3989): isChinaCountryCode : false
,I/SA      ( 3989): [OR] == networkStateCheck true ==
,I/SA      ( 3989): [OR] GetMyCountryZoneTask
,I/SA      ( 3989): [OR] onReceive END
,I/SA      ( 3989): [SRS] prepareGetMyCountryZone
,D/PhoneNumberLocatorBootCompletedReceiver( 1241): onReceive
,D/PhoneNumberLocatorBootCompletedReceiver( 1241): Phone number locator feature is dsiabled
,I/SCloudBackupReceiver( 5461): Other Intent
,I/SA      ( 3989): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
I/SELinux ( 5643): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5643):  
I/SELinux ( 5643):  
,I/SELinux ( 5643): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5643): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5643): >>>>> Normal User
,E/dalvikvm( 5643): >>>>> com.sec.android.app.voicenote [ userId:0 | appId:1000 ]
,D/com.samsung.app( 1447): [KK_EASY_Accu]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,E/SELinux ( 5643): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/com.samsung.app( 1447): [KK_EASY_Accu]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,D/Headlines( 4040): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,I/SA      ( 3989): [SSP] query invoked
,D/HeadlinesChannelUtil( 4040): getCountryCode(): countryCode = PL
W/WifiP2pStateTracker(  759): WifiP2pStateReceiver : android.net.wifi.LINK_CONFIGURATION_CHANGED
D/ConnectivityService(  759): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService(  759):    car=removed=[] added=[fe80::3a94:96ff:feb5:6dd/64,]
D/ConnectivityService(  759): handleConnectivityChange: setting default proxy info 
,D/ConnectivityService(  759): updateSourceRoutes : no source routing conditions
I/SA      ( 3989): [TPMU] GetMccFromDB : null
I/SA      ( 3989): [SCU] getMccFromPreferece mcc = 260
I/SA      ( 3989): [TPM] isNoProxy(default) : true
I/SA      ( 3989): [RC New] Execute method=[GET] start
,D/TimaKeyStoreProvider( 5643): in addTimaSignatureService
,D/Headlines( 4040): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
D/HeadlinesCardManager( 4040): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 4040): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 4040): queryCategory.  mRequest is not initialized.
,D/TimaKeyStoreProvider( 5643): Cannot add TimaSignature Service, License check Failed
D/HeadlinesCardManager( 4040): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 4040): requestUpdateNewsWelcomeCard : request update welcome card to content card.
,D/HeadlinesDataCenter( 4040): requestUpdateNewsWelcomeCard !!! no welcome card
,D/ActivityThread( 5643): Added TimaKesytore provider
,D/QuickConnect[1.1][2] ( 3311): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
I/QuickConnect[1.1][2] ( 3311): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,V/QuickConnect[1.1][2] ( 3311): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@425ed340
,D/RCPManagerService(  759): exchangeData() failure , invalid userId
,D/RCPManagerService(  759): exchangeData() failure , invalid userId
,D/WaitQueueForNetworkActivate( 4131): notifyNetworkActivated
,D/hcjo    ( 4131): AutoUpdateManager:IDLE:execute
D/InitializeManagerStateMachine( 4131): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine( 4131): exit::IDLE
,D/InitializeManagerStateMachine( 4131): entry::NETWORK_CHECK
D/InitializeManagerStateMachine( 4131): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 4131): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 4131): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 4131): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 4131): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 4131): entry::SUCCESS
,D/hcjo    ( 4131): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/hcjo    ( 4131): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/hcjo    ( 4131): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
D/InitializeManagerStateMachine( 4131): exit::SUCCESS
,D/InitializeManagerStateMachine( 4131): entry::IDLE
,D/dalvikvm(  759): GC_EXPLICIT freed 2726K, 58% free 23751K/55576K, paused 7ms+14ms, total 141ms
,V/KVNProvider( 5643): query uri : content://com.sec.android.app.voicenote.common.util.VNProvider/search_suggest_tag_query
,V/KVNProvider( 5643): getFindoCursor query string : 
,V/KVNProvider( 5643): getTagSearchCursor() tagSearchCursor count : 0
,I/iu.Environment( 1761): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 1761): num queued entries: 0
,I/iu.UploadsManager( 1761): num updated entries: 0
,I/iu.SyncManager( 1761): NEXT; no task
I/ActivityManager(  759): Killing 4590:com.sec.providers.settingsearch/u0a160 (adj 15): empty #43
,I/PhenotypeConfigurator( 1220): Scheduling Phenotype for one-off execution 9552 seconds from now (1449756725143)
,D/GetConfigurationSnapshotOperation( 1220): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1220): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,W/dalvikvm( 1220): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1220): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1220): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,I/dalvikvm( 1220): Could not find method android.net.Network.openConnection, referenced from method com.google.android.gms.http.g.a
W/dalvikvm( 1220): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,D/dalvikvm( 1220): VFY: replacing opcode 0x6e at 0x00bb
,I/GoogleURLConnFactory( 1220): Using platform SSLCertificateSocketFactory
,I/SA      ( 3989): [RC New] [v2liruge] api execute + 656
,I/SA      ( 3989): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,I/System.out( 3989): AsyncTask #2 calls detatch()
,I/SA      ( 3989): [TPMU] getNetworkMcc : 
,D/LocationManagerService(  759): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
I/SA      ( 3989): [SCU] saveMccToPreferece Start
,I/SA      ( 3989): [SCU] RegionMCC : 260
,I/SA      ( 3989): [SSP] query invoked
,I/SA      ( 3989): [TPMU] GetMccFromDB : null
I/SA      ( 3989): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 3989): [SCU] saveMccToPreferece End
I/SA      ( 3989): [RC New] executeRequest [v2liruge] end. 685
,I/SA      ( 3989): [RC New] Execute end
I/SA      ( 3989): [OR] GetMyCountryZoneTask mcc = 260
,I/SA      ( 3989): [OR] GetMyCountryZoneTask Success
,I/dalvikvm( 1220): Could not find method android.os.PowerManager.isInteractive, referenced from method com.google.android.gms.common.util.y.a
W/dalvikvm( 1220): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
,D/dalvikvm( 1220): VFY: replacing opcode 0x6e at 0x003d
,I/jxcore-log( 5151): BLE advertisement not supported: Build version is 19
I/jxcore-log( 5151): 
,I/System.out( 1220): Thread-107(HTTPLog):isShipBuild true
,I/System.out( 1220): Thread-107(HTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/dalvikvm( 1220): GC_CONCURRENT freed 1530K, 37% free 11879K/18744K, paused 5ms+5ms, total 56ms
,D/ConnectivityService(  759): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/STATUSBAR-NetworkController_dual( 1069): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
,D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews set mobileLabel[SIM_0] =
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 set mobileLabel[SIM_1] =
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set : simMode = 0
,D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set as slot1`s
,E/SMD     (  233): DCD ON
,E/WifiStateMachine(  759): CAPTIVE_PORTAL_EVENT_AUTHENTICATED
,I/HarmonyEASService(  759): Updating for all 1
,I/SurfaceFlinger(  242): id=18 Removed Uoast (12/13)
,I/SurfaceFlinger(  242): id=18 Removed Uoast (-2/13)
D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
I/ActivityManager(  759): Killing 4166:com.android.calendar/u0a142 (adj 15): empty #43
D/PowerManagerService(  759): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=759 (0x0)
D/PowerManagerService(  759): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=759, ws=WorkSource{1000}) (elapsedTime=3457)
,D/AmoledAdjustTimer(  759): prevTemp = 294, currTemp = 295, prevStep = 4, currStep = 4
,I/GAV2    ( 5491): Thread[GAThread,5,main]: No campaign data found.
,I/PCWCLIENTTRACE_SYSTEMReceiver( 5070): mConnectivityHandler : connected
,E/SMD     (  233): DCD ON
,W/PCWCLIENTTRACE_AccountUtil( 5070): [hasSamungAccount] - No Samsung Account
,W/linker  ( 5070): libterrier.so has text relocations. This is wasting memory and is a security risk. Please fix.
,I/CSTORAGE( 5070): ================================================
,I/CSTORAGE( 5070):  CSTORAGE_SKM_LIB v1.0.14
I/CSTORAGE( 5070): ================================================
D/dalvikvm( 5070): No JNI_OnLoad found in /system/lib/libterrier.so 0x425e7440, skipping init
,I/PCWCLIENTTRACE_SecurePreferencesJNI( 5070): [GetString-S]
,I/terrier ( 5070): v1.1.3q com.sec.pcw.device: getString function called
D/QSEECOMAPI: ( 5070): QSEECom_get_handle sb_length = 0x2040
,D/QSEECOMAPI: ( 5070): App is not loaded in QSEE
,D/QSEECOMAPI: ( 5070): Loaded image: APP id = 5
,D/QSEECOMAPI: ( 5070): QSEECom_dealloc_memory 
,D/QSEECOMAPI: ( 5070): QSEECom_shutdown_app, app_id = 5
,E/terrier ( 5070): com.sec.pcw.device: getString: failed to get string(-1)
,I/PCWCLIENTTRACE_SecurePreferencesJNI( 5070): [GetString-E]
,I/PCWCLIENTTRACE_PushUtil( 5070): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 5070): sales region : global
,I/PCWCLIENTTRACE_PushUtil( 5070): getPushTypeList : [SPP, GCM]
,E/PCWCLIENTTRACE_PCWHandler( 5070): [ensureRegistration] - No Samsung account
,W/ContextImpl(  759): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager(  759): waitForAlarm result :4
,V/AlarmManager(  759): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 298, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  759): stay LED for fully charged
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,D/Finsky  ( 3627): [358] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 3627): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  759): SIOP:: AP = 310, Delta = -20
,D/CaptivePortalTracker(  759): DelayedCaptiveCheckState{ when=-7ms what=2 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  759): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/CaptivePortalTracker(  759): Checking http://216.58.209.46/generate_204
,D/CaptivePortalTracker(  759): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker(  759): isCaptivePortal: ret=false rspCode=204
,D/CaptivePortalTracker(  759): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker(  759): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  759): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
,D/PreloadUpdateManagerStateMachine( 4131): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine( 4131): exit::IDLE
,D/PreloadUpdateManagerStateMachine( 4131): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 4131): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 4131): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 4131): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 4131): entry::IDLE
,E/Watchdog(  759): !@Sync 4
,E/SMD     (  233): DCD ON
,I/PowerManagerService(  759): [PWL] Off : 75s ago
,D/AmoledAdjustTimer(  759): prevTemp = 295, currTemp = 298, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,V/AlarmManager(  759): waitForAlarm result :8
,D/Headlines( 4040): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 4040): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 4040): Breath 17029 latestRequest time : 1449756724616 current time : 1449756741645
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 297, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  759): stay LED for fully charged
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = -10
,E/SMD     (  233): DCD ON
,D/AmoledAdjustTimer(  759): prevTemp = 298, currTemp = 297, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,W/ContextImpl(  759): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  233): DCD ON
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 295, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
,D/BatteryService(  759): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,E/SMD     (  233): DCD ON
,D/AmoledAdjustTimer(  759): prevTemp = 297, currTemp = 295, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  759): stay LED for fully charged
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  759): !@Sync 5
,E/SMD     (  233): DCD ON
,I/PowerManagerService(  759): [PWL] Off : 105s ago
,D/AmoledAdjustTimer(  759): prevTemp = 295, currTemp = 293, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,W/ContextImpl(  759): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  233): DCD ON
,V/AlarmManager(  759): waitForAlarm result :8
,D/Headlines( 4040): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 4040): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 4040): Breath 47017 latestRequest time : 1449756724616 current time : 1449756771634
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
,D/BatteryService(  759): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,E/SMD     (  233): DCD ON
,D/AmoledAdjustTimer(  759): prevTemp = 293, currTemp = 292, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,V/AlarmManager(  759): waitForAlarm result :8
,V/AlarmManager(  759): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1069): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
,D/BatteryService(  759): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,E/SMD     (  233): DCD ON
,D/AmoledAdjustTimer(  759): prevTemp = 292, currTemp = 291, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,W/ContextImpl(  759): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  759): stay LED for fully charged
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  759): !@Sync 6
,E/SMD     (  233): DCD ON
,D/AmoledAdjustTimer(  759): prevTemp = 291, currTemp = 290, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,V/AlarmManager(  759): waitForAlarm result :8
,D/Headlines( 4040): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 4040): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 4040): Breath 77012 latestRequest time : 1449756724616 current time : 1449756801628
,I/PowerManagerService(  759): [PWL] Off : 140s ago
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,E/SMD     (  233): DCD ON
,D/AmoledAdjustTimer(  759): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,W/ContextImpl(  759): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  233): DCD ON
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:6, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  759): stay LED for fully charged
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1945): Disconnected process message: 10
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,E/SMD     (  233): DCD ON
,D/AmoledAdjustTimer(  759): prevTemp = 290, currTemp = 289, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-3, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
,D/BatteryService(  759): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,E/SMD     (  233): DCD ON
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  759): !@Sync 7
,E/SMD     (  233): DCD ON
,D/AmoledAdjustTimer(  759): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,W/ContextImpl(  759): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  233): DCD ON
,V/AlarmManager(  759): waitForAlarm result :8
,D/Headlines( 4040): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 4040): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 4040): Breath 107016 latestRequest time : 1449756724616 current time : 1449756831632
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-3, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  759): stay LED for fully charged
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,E/SMD     (  233): DCD ON
,D/AmoledAdjustTimer(  759): prevTemp = 289, currTemp = 288, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,V/AlarmManager(  759): waitForAlarm result :8
,V/AlarmManager(  759): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1069): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,I/PowerManagerService(  759): [PWL] Off : 180s ago
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-1, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  759): stay LED for fully charged
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
D/HeadsetStateMachine( 1945): Disconnected process message: 10
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,E/SMD     (  233): DCD ON
,D/AmoledAdjustTimer(  759): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,W/ContextImpl(  759): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  233): DCD ON
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  759): stay LED for fully charged
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  759): !@Sync 8
,E/SMD     (  233): DCD ON
,D/AmoledAdjustTimer(  759): prevTemp = 288, currTemp = 287, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,V/AlarmManager(  759): waitForAlarm result :8
,D/Headlines( 4040): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 4040): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 4040): Breath 137020 latestRequest time : 1449756724616 current time : 1449756861637
,D/Headlines( 4040): stop 
,D/Headlines( 4040): Breath.onDestroy : 
,I/ActivityManager(  759): Killing 4361:com.sec.android.widgetapp.SPlannerAppWidget/u0a143 (adj 15): empty #43
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  759): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,W/ContextImpl(  759): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  233): DCD ON
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  759): stay LED for fully charged
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
D/HeadsetStateMachine( 1945): Disconnected process message: 10
,I/jxcore-log( 5151): Connected to the server!
I/jxcore-log( 5151): 
,I/chromium( 5151): [INFO:CONSOLE(63)] "logCallback Connected to the server", source: file:///android_asset/www/js/thali_main.js (63)
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,E/SMD     (  233): DCD ON
,D/AmoledAdjustTimer(  759): prevTemp = 287, currTemp = 286, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
,D/BatteryService(  759): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  759): !@Sync 9
,E/SMD     (  233): DCD ON
,I/PowerManagerService(  759): [PWL] Off : 225s ago
,D/AmoledAdjustTimer(  759): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,W/ContextImpl(  759): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  233): DCD ON
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
,D/BatteryService(  759): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  759): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,V/AlarmManager(  759): waitForAlarm result :8
,V/AlarmManager(  759): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1069): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
,D/BatteryService(  759): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,E/SMD     (  233): DCD ON
,D/AmoledAdjustTimer(  759): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/TimaService(  759): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  759): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  759): TimaServiceHandler.handleMessage what =1
,I/TLC_TIMA_PKM_initialize(  759): initializing...
,I/TLC_TIMA_PKM_initialize(  759): root = /firmware/image, root_strlen = 15
,I/TLC_TIMA_PKM_initialize(  759): process = tima_pkm, process_strlen = 8
,I/TZ: qc_tlc_communication(  759): root = /firmware/image, root_len = 15
,I/TZ: qc_tlc_communication(  759): process = tima_pkm, process_strlen = 8
I/TZ: qc_tlc_communication(  759): aligned max_sendmsg_size = 262208 = 0x40040
,I/TZ: qc_tlc_communication(  759): aligned max_recvmsg_size = 262208 = 0x40040
,I/TZ: qc_tlc_communication(  759): max_message_size = 524416 = 0x80080
,D/QSEECOMAPI: (  759): QSEECom_get_handle sb_length = 0x80080
,D/QSEECOMAPI: (  759): App is not loaded in QSEE
,D/QSEECOMAPI: (  759): Loaded image: APP id = 5
,I/TZ: qc_tlc_communication(  759): TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded
,E/SMD     (  233): DCD ON
,I/TLC_TIMA_PKM_initialize(  759): Trustlet response is completed
,W/ContextImpl(  759): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  233): DCD ON
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-4, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  759): stay LED for fully charged
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
,I/TLC_TIMA_PKM_measure_kernel(  759): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  759): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  759): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  759): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog(  759): !@Sync 10
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,E/SMD     (  233): DCD ON
,D/AmoledAdjustTimer(  759): prevTemp = 286, currTemp = 285, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  759): stay LED for fully charged
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  759): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,W/ContextImpl(  759): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,E/SMD     (  233): DCD ON
,I/PowerManagerService(  759): [PWL] Off : 275s ago
,V/AlarmManager(  759): waitForAlarm result :4
,V/AlarmManager(  759): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,I/SELinux ( 5760): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5760):  
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-3, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
,D/BatteryService(  759): stay LED for fully charged
,D/AmoledAdjustTimer(  759): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/dalvikvm(  243): GC_EXPLICIT freed 43K, 50% free 9510K/18744K, paused 27ms+40ms, total 367ms
,D/dalvikvm(  243): GC_EXPLICIT freed <1K, 50% free 9510K/18744K, paused 21ms+15ms, total 172ms
,I/SELinux ( 5760): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5760):  
I/SELinux ( 5760):  
,I/SELinux ( 5760): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5760): [DEBUG] seapp_context_lookup: seinfoCategory = default
,E/dalvikvm( 5760): >>>>> Normal User
,E/dalvikvm( 5760): >>>>> com.blurb.checkout [ userId:0 | appId:10075 ]
,D/dalvikvm(  243): GC_EXPLICIT freed <1K, 50% free 9510K/18744K, paused 6ms+4ms, total 49ms
,E/SELinux ( 5760): [DEBUG] seapp_context_lookup: seinfoCategory = default
,D/TimaKeyStoreProvider( 5760): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5760): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5760): Added TimaKesytore provider
,W/ActivityManager(  759): Permission Denial: getCurrentUser() from pid=5760, uid=10075 requires android.permission.INTERACT_ACROSS_USERS
,I/ActivityManager(  759): Killing 4527:com.sec.phone/1001 (adj 15): empty #43
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,E/Watchdog(  759): !@Sync 11
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,E/SMD     (  233): DCD ON
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
D/BatteryService(  759): stay LED for fully charged
,D/AmoledAdjustTimer(  759): prevTemp = 285, currTemp = 284, prevStep = 4, currStep = 4
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  233): DCD ON
,W/ContextImpl(  759): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,E/SMD     (  233): DCD ON
,D/AmoledAdjustTimer(  759): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,V/AlarmManager(  759): waitForAlarm result :8
,V/AlarmManager(  759): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1069): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,E/SMD     (  233): DCD ON
,D/AmoledAdjustTimer(  759): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-3, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
,D/BatteryService(  759): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
D/HeadsetStateMachine( 1945): Disconnected process message: 10
,E/SMD     (  233): DCD ON
,W/ContextImpl(  759): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  233): DCD ON
,E/Watchdog(  759): !@Sync 12
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  759): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-4, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
,D/BatteryService(  759): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,E/SMD     (  233): DCD ON
,D/AmoledAdjustTimer(  759): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
,D/BatteryService(  759): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
,W/ContextImpl(  759): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  233): DCD ON
,I/PowerManagerService(  759): [PWL] Off : 330s ago
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,E/SMD     (  233): DCD ON
,D/AmoledAdjustTimer(  759): prevTemp = 284, currTemp = 283, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,E/Watchdog(  759): !@Sync 13
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  759): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
,D/BatteryService(  759): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
,E/SMD     (  233): DCD ON
,W/ContextImpl(  759): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,E/SMD     (  233): DCD ON
,D/AmoledAdjustTimer(  759): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,V/AlarmManager(  759): waitForAlarm result :8
,V/AlarmManager(  759): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1069): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,E/SMD     (  233): DCD ON
,D/AmoledAdjustTimer(  759): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  759): stay LED for fully charged
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1945): Disconnected process message: 10
,E/SMD     (  233): DCD ON
,W/ContextImpl(  759): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/dalvikvm(  759): GC_CONCURRENT freed 3479K, 58% free 23733K/55576K, paused 33ms+68ms, total 672ms
,E/SMD     (  233): DCD ON
,E/Watchdog(  759): !@Sync 14
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  759): prevTemp = 283, currTemp = 282, prevStep = 4, currStep = 4
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  759): stay LED for fully charged
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,E/SMD     (  233): DCD ON
,D/AmoledAdjustTimer(  759): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-3, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  759): stay LED for fully charged
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
,W/ContextImpl(  759): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  233): DCD ON
,I/PowerManagerService(  759): [PWL] Off : 390s ago
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,E/SMD     (  233): DCD ON
,D/AmoledAdjustTimer(  759): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-4, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
,D/BatteryService(  759): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/HeadsetStateMachine( 1945): Disconnected process message: 10
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,E/Watchdog(  759): !@Sync 15
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  759): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
,D/BatteryService(  759): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
,E/SMD     (  233): DCD ON
,W/ContextImpl(  759): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,E/SMD     (  233): DCD ON
,D/AmoledAdjustTimer(  759): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  759): stay LED for fully charged
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
,V/AlarmManager(  759): waitForAlarm result :8
,V/AlarmManager(  759): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1069): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  759): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
,D/BatteryService(  759): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,W/ContextImpl(  759): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  233): DCD ON
,E/Watchdog(  759): !@Sync 16
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  759): prevTemp = 282, currTemp = 281, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,E/SMD     (  233): DCD ON
,D/AmoledAdjustTimer(  759): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-1, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
,D/BatteryService(  759): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,W/ContextImpl(  759): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,I/PowerManagerService(  759): [PWL] Off : 455s ago
,D/AmoledAdjustTimer(  759): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
,D/BatteryService(  759): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,E/Watchdog(  759): !@Sync 17
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  759): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-1, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  759): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
D/UiModeManager(  759): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,W/ContextImpl(  759): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,E/SMD     (  233): DCD ON
,D/AmoledAdjustTimer(  759): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,V/AlarmManager(  759): waitForAlarm result :8
,V/AlarmManager(  759): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1069): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  759): stay LED for fully charged
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  759): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-6, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  759): stay LED for fully charged
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
,W/ContextImpl(  759): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  233): DCD ON
,E/Watchdog(  759): !@Sync 18
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  759): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  759): stay LED for fully charged
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,E/SMD     (  233): DCD ON
,D/AmoledAdjustTimer(  759): prevTemp = 281, currTemp = 280, prevStep = 4, currStep = 4
,W/ContextImpl(  759): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  759): stay LED for fully charged
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  759): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,E/Watchdog(  759): !@Sync 19
,E/SMD     (  233): DCD ON
,I/PowerManagerService(  759): [PWL] Off : 525s ago
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  759): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,W/ContextImpl(  759): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-3, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
,D/BatteryService(  759): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  759): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,V/AlarmManager(  759): waitForAlarm result :8
,V/AlarmManager(  759): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1069): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  759): stay LED for fully charged
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
,E/SMD     (  233): DCD ON
D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  759): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,D/TimaService(  759): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  759): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  759): TimaServiceHandler.handleMessage what =1
,E/SMD     (  233): DCD ON
,W/ContextImpl(  759): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-1, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
,D/BatteryService(  759): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
,E/SMD     (  233): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  759): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  759): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  759): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  759): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog(  759): !@Sync 20
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  759): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  759): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,W/ContextImpl(  759): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  233): DCD ON
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-3, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
D/BatteryService(  759): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  759): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  759): stay LED for fully charged
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,E/Watchdog(  759): !@Sync 21
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  759): prevTemp = 280, currTemp = 279, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-5, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  759): stay LED for fully charged
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  759): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,V/AlarmManager(  759): waitForAlarm result :8
,V/AlarmManager(  759): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1069): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  759): stay LED for fully charged
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,I/PowerManagerService(  759): [PWL] Off : 600s ago
,V/AlarmManager(  759): waitForAlarm result :8
,D/LightsService(  759): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
I/SensorManagerA(  759): getReportingMode :: sensor.mType = 5
D/Sensors (  759): LightSensor setDelay = 200000000
D/Sensors (  759): LightSensor setSensorDelay = 200000000
D/Sensors (  759): Light sensor flush: not enabled 0
D/Sensors (  759): LightSensor enable = 1
D/Sensors (  759): LightSensor enableSensor = 1
D/SensorManager(  759): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
,D/Sensors (  759): LightSensor enable = 0
,D/Sensors (  759): LightSensor enableSensor = 0
,D/LightsService(  759): [SvcLED]  onSensorChanged::light value = 2
,D/SensorManager(  759): unregisterListener ::   
D/LightsService(  759): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  759): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
,D/BatteryService(  759): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,E/Watchdog(  759): !@Sync 22
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  759): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-4, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
,D/BatteryService(  759): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  759): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-5, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  759): stay LED for fully charged
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  759): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-1, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  759): stay LED for fully charged
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,E/Watchdog(  759): !@Sync 23
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  759): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-5, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  759): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  759): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,V/AlarmManager(  759): waitForAlarm result :8
,V/AlarmManager(  759): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager(  759): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManager(  759): <AppSync3 Whitelist>
,V/AlarmManager(  759): (AppSync) ### 0 added ###
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1069): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  759): stay LED for fully charged
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  759): prevTemp = 279, currTemp = 278, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-5, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  759): stay LED for fully charged
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,E/Watchdog(  759): !@Sync 24
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  759): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,I/PowerManagerService(  759): [PWL] Off : 680s ago
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  759): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  759): stay LED for fully charged
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  759): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,E/Watchdog(  759): !@Sync 25
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  759): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-6, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  759): stay LED for fully charged
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  759): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,V/AlarmManager(  759): waitForAlarm result :8
,V/AlarmManager(  759): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1069): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
,D/BatteryService(  759): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  759): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-5, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  759): stay LED for fully charged
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,E/Watchdog(  759): !@Sync 26
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  759): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-3, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
,D/BatteryService(  759): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  759): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
,D/BatteryService(  759): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  759): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
,D/BatteryService(  759): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,E/Watchdog(  759): !@Sync 27
,E/SMD     (  233): DCD ON
,I/PowerManagerService(  759): [PWL] Off : 765s ago
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  759): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  759): stay LED for fully charged
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,V/AlarmManager(  759): waitForAlarm result :8
,V/AlarmManager(  759): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1069): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  759): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  759): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
,D/BatteryService(  759): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,E/Watchdog(  759): !@Sync 28
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  759): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
,D/BatteryService(  759): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  759): prevTemp = 278, currTemp = 277, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-5, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  759): stay LED for fully charged
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  759): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-4, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  759): stay LED for fully charged
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,E/Watchdog(  759): !@Sync 29
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  759): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
,D/BatteryService(  759): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
D/HeadsetStateMachine( 1945): Disconnected process message: 10
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,V/AlarmManager(  759): waitForAlarm result :8
,V/AlarmManager(  759): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1069): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  759): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,D/dalvikvm(  759): GC_CONCURRENT freed 3452K, 57% free 23737K/54996K, paused 35ms+58ms, total 652ms
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-5, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
,D/BatteryService(  759): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/TimaService(  759): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  759): TimaServiceHandler.handleMessage what =1
,D/TimaService(  759): TIMA: checkEvent, operation: 50000 subject: 10000
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  759): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-3, charge type:1, power sharing:false
,D/BatteryService(  759): stay LED for fully charged
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
,E/SMD     (  233): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  759): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  759): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  759): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  759): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog(  759): !@Sync 30
,E/SMD     (  233): DCD ON
,I/PowerManagerService(  759): [PWL] Off : 855s ago
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  759): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
,D/BatteryService(  759): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  759): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-3, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  759): stay LED for fully charged
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  759): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-8, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  759): stay LED for fully charged
,E/SMD     (  233): DCD ON
D/UiModeManager(  759): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/Watchdog(  759): !@Sync 31
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  759): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/BatteryService(  759): stay LED for fully charged
D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,V/AlarmManager(  759): waitForAlarm result :8
,V/AlarmManager(  759): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1069): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  759): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/BatteryService(  759): stay LED for fully charged
D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  759): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
,D/BatteryService(  759): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/Watchdog(  759): !@Sync 32
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  759): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-11, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  759): stay LED for fully charged
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  759): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-9, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  759): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
D/UiModeManager(  759): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  759): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  759): stay LED for fully charged
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/Watchdog(  759): !@Sync 33
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,I/PowerManagerService(  759): [PWL] Off : 950s ago
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  759): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  759): stay LED for fully charged
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,V/AlarmManager(  759): waitForAlarm result :8
,V/AlarmManager(  759): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1069): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  759): prevTemp = 277, currTemp = 276, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,V/AlarmManager(  759): waitForAlarm result :4
,V/AlarmManager(  759): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,I/GoogleURLConnFactory( 1220): Using platform SSLCertificateSocketFactory
,I/PhenotypeConfigurator( 1220): Scheduling Phenotype every 14400 seconds, with flex of 1800 seconds
,D/ConnectivityService(  759): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/STATUSBAR-NetworkController_dual( 1069): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
,D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews set mobileLabel[SIM_0] =
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 set mobileLabel[SIM_1] =
,D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 GONE
,D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set : simMode = 0
,D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set as slot1`s
,W/PhenotypeConfigurator( 1220): Server returned 404
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  759): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,E/Watchdog(  759): !@Sync 34
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-9, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  759): stay LED for fully charged
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  759): prevTemp = 276, currTemp = 277, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-6, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  759): stay LED for fully charged
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  759): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
,D/BatteryService(  759): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  759): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,E/Watchdog(  759): !@Sync 35
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  759): stay LED for fully charged
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  759): prevTemp = 277, currTemp = 276, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,V/AlarmManager(  759): waitForAlarm result :8
,V/AlarmManager(  759): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1069): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  759): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-10, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  759): stay LED for fully charged
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  759): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/Watchdog(  759): !@Sync 36
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  759): stay LED for fully charged
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  759): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-4, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  759): stay LED for fully charged
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,I/PowerManagerService(  759): [PWL] Off : 1050s ago
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  759): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
,D/BatteryService(  759): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  759): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/Watchdog(  759): !@Sync 37
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-8, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  759): stay LED for fully charged
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  759): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  759): stay LED for fully charged
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,V/AlarmManager(  759): waitForAlarm result :8
,V/AlarmManager(  759): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1069): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  759): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  759): stay LED for fully charged
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  759): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/Watchdog(  759): !@Sync 38
,E/SMD     (  233): DCD ON
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-4, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  759): stay LED for fully charged
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  759): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  759): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
,D/BatteryService(  759): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  759): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/Watchdog(  759): !@Sync 39
,E/SMD     (  233): DCD ON
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-1, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
,D/BatteryService(  759): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  759): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-9, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  759): stay LED for fully charged
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,V/AlarmManager(  759): waitForAlarm result :8
,V/AlarmManager(  759): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1069): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  759): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-4, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  759): stay LED for fully charged
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,D/TimaService(  759): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  759): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  759): TimaServiceHandler.handleMessage what =1
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  759): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  759): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  759): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  759): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  759): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/Watchdog(  759): !@Sync 40
,E/SMD     (  233): DCD ON
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-1, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  759): stay LED for fully charged
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,I/PowerManagerService(  759): [PWL] Off : 1155s ago
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  759): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  759): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-3, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  759): stay LED for fully charged
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  759): prevTemp = 276, currTemp = 275, prevStep = 4, currStep = 4
,E/Watchdog(  759): !@Sync 41
,E/SMD     (  233): DCD ON
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-10, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
,D/BatteryService(  759): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  759): prevTemp = 275, currTemp = 276, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-4, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
,D/BatteryService(  759): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,V/AlarmManager(  759): waitForAlarm result :8
,V/AlarmManager(  759): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1069): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,V/AlarmManager(  759): waitForAlarm result :8
,I/SensorManagerA(  759): getReportingMode :: sensor.mType = 5
,D/LightsService(  759): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
D/Sensors (  759): LightSensor setDelay = 200000000
D/Sensors (  759): LightSensor setSensorDelay = 200000000
D/Sensors (  759): Light sensor flush: not enabled 0
D/Sensors (  759): LightSensor enable = 1
D/Sensors (  759): LightSensor enableSensor = 1
D/SensorManager(  759): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
,D/LightsService(  759): [SvcLED]  onSensorChanged::light value = 0
D/Sensors (  759): LightSensor enable = 0
D/Sensors (  759): LightSensor enableSensor = 0
,D/SensorManager(  759): unregisterListener ::   
D/LightsService(  759): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  759): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-9, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  759): stay LED for fully charged
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,E/Watchdog(  759): !@Sync 42
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  759): prevTemp = 276, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-4, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  759): stay LED for fully charged
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  759): prevTemp = 275, currTemp = 276, prevStep = 4, currStep = 4
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-7, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  759): stay LED for fully charged
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  759): prevTemp = 276, currTemp = 275, prevStep = 4, currStep = 4
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-11, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  759): stay LED for fully charged
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,E/Watchdog(  759): !@Sync 43
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  759): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-11, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  759): stay LED for fully charged
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  759): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-11, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
,D/BatteryService(  759): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
D/HeadsetStateMachine( 1945): Disconnected process message: 10
,E/SMD     (  233): DCD ON
,V/AlarmManager(  759): waitForAlarm result :8
,V/AlarmManager(  759): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager(  759): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManager(  759): <AppSync3 Whitelist>
,V/AlarmManager(  759): (AppSync) ### 0 added ###
D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 1069): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  759): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,I/PowerManagerService(  759): [PWL] Off : 1265s ago
,E/SMD     (  233): DCD ON
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-9, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
,D/BatteryService(  759): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,E/Watchdog(  759): !@Sync 44
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  759): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,D/dalvikvm(  759): GC_CONCURRENT freed 3445K, 57% free 23757K/54996K, paused 35ms+64ms, total 666ms
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-8, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  759): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
D/HeadsetStateMachine( 1945): Disconnected process message: 10
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  759): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-3, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
,D/BatteryService(  759): stay LED for fully charged
D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  759): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  759): stay LED for fully charged
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,E/Watchdog(  759): !@Sync 45
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  759): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:10, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  759): stay LED for fully charged
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  759): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-6, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  759): stay LED for fully charged
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,V/AlarmManager(  759): waitForAlarm result :8
,V/AlarmManager(  759): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1069): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  759): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  759): stay LED for fully charged
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,E/Watchdog(  759): !@Sync 46
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  759): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-9, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  759): stay LED for fully charged
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  759): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  759): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  759): stay LED for fully charged
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,E/Watchdog(  759): !@Sync 47
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  759): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  759): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
D/UiModeManager(  759): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  759): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-6, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  759): stay LED for fully charged
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,V/AlarmManager(  759): waitForAlarm result :8
,V/AlarmManager(  759): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1069): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,I/PowerManagerService(  759): [PWL] Off : 1380s ago
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  759): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-10, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
,D/BatteryService(  759): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,E/Watchdog(  759): !@Sync 48
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  759): prevTemp = 275, currTemp = 274, prevStep = 4, currStep = 4
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-5, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
,D/BatteryService(  759): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  759): prevTemp = 274, currTemp = 275, prevStep = 4, currStep = 4
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-10, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  759): stay LED for fully charged
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,E/SMD     (  233): DCD ON
D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  759): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-6, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  759): stay LED for fully charged
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,E/Watchdog(  759): !@Sync 49
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  759): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-3, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
D/BatteryService(  759): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  759): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-6, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
,D/BatteryService(  759): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,V/AlarmManager(  759): waitForAlarm result :8
,V/AlarmManager(  759): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1069): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  759): prevTemp = 275, currTemp = 274, prevStep = 4, currStep = 4
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
,D/BatteryService(  759): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,D/TimaService(  759): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  759): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  759): TimaServiceHandler.handleMessage what =1
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  759): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  759): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  759): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  759): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog(  759): !@Sync 50
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  759): prevTemp = 274, currTemp = 275, prevStep = 4, currStep = 4
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-6, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  759): stay LED for fully charged
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  759): prevTemp = 275, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-6, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  759): stay LED for fully charged
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  759): prevTemp = 274, currTemp = 275, prevStep = 4, currStep = 4
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
,D/BatteryService(  759): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,E/Watchdog(  759): !@Sync 51
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  759): prevTemp = 275, currTemp = 274, prevStep = 4, currStep = 4
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-7, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
,D/BatteryService(  759): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  759): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,V/AlarmManager(  759): waitForAlarm result :8
,V/AlarmManager(  759): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1069): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-9, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  759): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,I/PowerManagerService(  759): [PWL] Off : 1500s ago
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  759): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-5, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  759): stay LED for fully charged
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,E/Watchdog(  759): !@Sync 52
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  759): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-8, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
,D/BatteryService(  759): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  759): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-10, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  759): stay LED for fully charged
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  759): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-4, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
D/BatteryService(  759): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
D/HeadsetStateMachine( 1945): Disconnected process message: 10
,E/SMD     (  233): DCD ON
,E/Watchdog(  759): !@Sync 53
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  759): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-7, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
,D/BatteryService(  759): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1945): Disconnected process message: 10
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  759): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,V/AlarmManager(  759): waitForAlarm result :8
,V/AlarmManager(  759): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1069): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
,D/BatteryService(  759): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  759): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  759): stay LED for fully charged
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,E/Watchdog(  759): !@Sync 54
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  759): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-12, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  759): stay LED for fully charged
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  759): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-9, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  759): stay LED for fully charged
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  759): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-8, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  759): stay LED for fully charged
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,E/Watchdog(  759): !@Sync 55
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  759): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-9, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
,D/BatteryService(  759): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  759): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,V/AlarmManager(  759): waitForAlarm result :8
,V/AlarmManager(  759): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1069): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-4, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
,D/BatteryService(  759): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
D/HeadsetStateMachine( 1945): Disconnected process message: 10
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,I/PowerManagerService(  759): [PWL] Off : 1625s ago
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  759): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-3, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  759): stay LED for fully charged
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,E/Watchdog(  759): !@Sync 56
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  759): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-4, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  759): stay LED for fully charged
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  759): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
,D/BatteryService(  759): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  759): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-4, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  759): stay LED for fully charged
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,E/Watchdog(  759): !@Sync 57
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  759): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:6, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  759): stay LED for fully charged
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  759): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,V/AlarmManager(  759): waitForAlarm result :8
,V/AlarmManager(  759): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1069): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-8, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
,D/BatteryService(  759): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  759): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-4, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
,D/BatteryService(  759): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,E/Watchdog(  759): !@Sync 58
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  759): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-13, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
,D/BatteryService(  759): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  759): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-1, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  759): stay LED for fully charged
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  759): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-12, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  759): stay LED for fully charged
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,E/Watchdog(  759): !@Sync 59
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  759): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  759): stay LED for fully charged
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/dalvikvm(  759): GC_CONCURRENT freed 3348K, 57% free 23880K/54804K, paused 31ms+17ms, total 372ms
,E/SMD     (  233): DCD ON
,V/AlarmManager(  759): waitForAlarm result :8
,V/AlarmManager(  759): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1069): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  759): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
,D/BatteryService(  759): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/TimaService(  759): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  759): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  759): TimaServiceHandler.handleMessage what =1
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  759): prevTemp = 274, currTemp = 273, prevStep = 4, currStep = 4
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-8, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  759): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
D/UiModeManager(  759): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/TLC_TIMA_PKM_measure_kernel(  759): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  759): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,E/SMD     (  233): DCD ON
D/TimaService(  759): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  759): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog(  759): !@Sync 60
,E/SMD     (  233): DCD ON
,I/PowerManagerService(  759): [PWL] Off : 1755s ago
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  759): prevTemp = 273, currTemp = 274, prevStep = 4, currStep = 4
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  759): stay LED for fully charged
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  759): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-8, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  759): stay LED for fully charged
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  759): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  759): stay LED for fully charged
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
D/HeadsetStateMachine( 1945): Disconnected process message: 10
,E/SMD     (  233): DCD ON
,E/Watchdog(  759): !@Sync 61
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  759): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-3, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
,D/BatteryService(  759): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,V/AlarmManager(  759): waitForAlarm result :8
,V/AlarmManager(  759): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1069): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,I/ProcessStatsService(  759): Prepared write state in 160ms
,I/ProcessStatsService(  759): Prepared write state in 163ms
,I/ProcessStatsService(  759): Prepared write state in 60ms
,I/ProcessStatsService(  759): Pruning old procstats: /data/system/procstats/state-2015-12-09-19-25-28.bin
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  759): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-1, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
,D/BatteryService(  759): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  759): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-10, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
,D/BatteryService(  759): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,E/Watchdog(  759): !@Sync 62
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  759): prevTemp = 274, currTemp = 273, prevStep = 4, currStep = 4
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-8, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  759): stay LED for fully charged
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  759): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  759): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-5, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
,D/BatteryService(  759): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  233): DCD ON
,E/Watchdog(  759): !@Sync 63
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  759): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,E/SMD     (  233): DCD ON
,V/AlarmManager(  759): waitForAlarm result :8
,V/AlarmManager(  759): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager(  759): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManager(  759): <AppSync3 Whitelist>
,V/AlarmManager(  759): (AppSync) ### 0 added ###
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1069): handleTimeUpdate
,I/ActivityManager(  759): Killing 5293:com.samsung.android.provider.shootingmodeprovider/u0a162 (adj 15): empty for 1803s
,I/ActivityManager(  759): Killing 5280:com.sec.kidsplat.installer/u0a158 (adj 15): empty for 1804s
,I/ActivityManager(  759): Killing 5266:com.samsung.helphub/1000 (adj 15): empty for 1804s
,I/ActivityManager(  759): Killing 5253:com.samsung.android.magazine.service/u0a106 (adj 15): empty for 1804s
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,I/ActivityManager(  759): Killing 5235:com.samsung.android.app.watchmanagerstub/u0a100 (adj 15): empty for 1804s
,I/ActivityManager(  759): Killing 5214:com.google.android.apps.docs/u0a90 (adj 15): empty for 1804s
,I/ActivityManager(  759): Killing 5192:com.sec.android.service.cm/u0a78 (adj 15): empty for 1805s
,I/ActivityManager(  759): Killing 4614:com.samsung.android.app.assistantmenu/1000 (adj 15): empty for 1805s
,I/ActivityManager(  759): Killing 4285:com.android.mms/u0a48 (adj 15): empty for 1805s
,I/ActivityManager(  759): Killing 5134:com.samsung.android.sdk.samsunglink/u0a42 (adj 15): empty for 1805s
,I/ActivityManager(  759): Killing 4191:com.sec.android.app.shealth/u0a35 (adj 15): empty for 1806s
,I/ActivityManager(  759): Killing 5084:com.samsung.android.app.galaxyfinder/u0a34 (adj 15): empty for 1806s
,I/ActivityManager(  759): Killing 5056:com.android.musicfx/u0a24 (adj 15): empty for 1806s
,I/ActivityManager(  759): Killing 5042:com.samsung.groupcast/u0a15 (adj 15): empty for 1807s
,I/ActivityManager(  759): Killing 5028:com.google.android.partnersetup/u0a14 (adj 15): empty for 1807s
,I/ActivityManager(  759): Killing 5012:com.sec.android.inputmethod/1000 (adj 15): empty for 1807s
,I/ActivityManager(  759): Killing 4956:com.android.defcontainer/u0a6 (adj 15): empty for 1807s
,I/ActivityManager(  759): Killing 4487:com.sec.android.app.music:service/u0a150 (adj 15): empty for 1858s
,D/CountryDetector(  759): No listener is left
,E/SMD     (  233): DCD ON
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  759): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  233): DCD ON
,V/AlarmManager(  759): waitForAlarm result :4
,V/NetworkStats(  759): performPollLocked(flags=0x3)
D/NtpTrustedTime(  759): currentTimeMillis() cache hit
,V/AlarmManager(  759): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,V/AlarmManager(  759): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  759): stay LED for fully charged
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/NtpTrustedTime(  759): currentTimeMillis() cache hit
V/NetworkStats(  759): performPollLocked() took 288ms
,D/NtpTrustedTime(  759): currentTimeMillis() cache hit
,D/NtpTrustedTime(  759): currentTimeMillis() cache hit
,I/ActivityManager(  759): Killing 5360:com.vlingo.midas/u0a33 (adj 15): empty for 1801s
,I/ActivityManager(  759): Killing 5430:com.samsung.klmsagent/u0a18 (adj 15): empty for 1801s
,I/ActivityManager(  759): Killing 5417:com.sec.android.fotaclient/u0a10 (adj 15): empty for 1801s
,I/ActivityManager(  759): Killing 3896:com.sec.android.diagmonagent/1000 (adj 15): empty for 1801s
,I/ActivityManager(  759): Killing 5394:com.sec.android.cloudagent/u0a2 (adj 15): empty for 1801s
,I/ActivityManager(  759): Killing 3855:com.google.android.music:main/u0a122 (adj 15): empty for 1801s
,I/ActivityManager(  759): Killing 5070:com.sec.pcw.device/1000 (adj 15): empty for 1801s
,I/ActivityManager(  759): Killing 1312:com.android.settings/1000 (adj 15): empty for 1802s
,I/ActivityManager(  759): Killing 5558:com.sec.android.provider.badge/u0a72 (adj 15): empty for 1802s
,I/SensorManagerA(  759): getReportingMode :: sensor.mType = 5
,D/Sensors (  759): LightSensor setDelay = 200000000
,D/Sensors (  759): LightSensor setSensorDelay = 200000000
,D/Sensors (  759): Light sensor flush: not enabled 0
D/Sensors (  759): LightSensor enable = 1
,D/Sensors (  759): LightSensor enableSensor = 1
,D/SensorManager(  759): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
D/LightsService(  759): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
,D/LightsService(  759): [SvcLED]  onSensorChanged::light value = 0
D/Sensors (  759): LightSensor enable = 0
D/Sensors (  759): LightSensor enableSensor = 0
,D/SensorManager(  759): unregisterListener ::   
D/LightsService(  759): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,I/EventLogService( 1761): Aggregate from 1449756645924 (log), 1449756645924 (data)
,V/GLSActivity( 1308): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1308): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/dalvikvm( 1308): VFY: unable to find class referenced in signature (Landroid/net/Network;)
E/dalvikvm( 1308): Could not find class 'android.net.Network', referenced from method com.google.android.gms.http.l.a
W/dalvikvm( 1308): VFY: unable to resolve check-cast 229 (Landroid/net/Network;) in Lcom/google/android/gms/http/l;
,D/dalvikvm( 1308): VFY: replacing opcode 0x1f at 0x0011
I/dalvikvm( 1308): Could not find method android.os.PowerManager.isInteractive, referenced from method com.google.android.gms.common.util.y.a
W/dalvikvm( 1308): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
,D/dalvikvm( 1308): VFY: replacing opcode 0x6e at 0x003d
,I/System.out( 1308): Thread-53(HTTPLog):isShipBuild true
,I/System.out( 1308): Thread-53(HTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/dalvikvm( 1308): GC_CONCURRENT freed 1987K, 43% free 10838K/18744K, paused 4ms+4ms, total 41ms
,D/ConnectivityService(  759): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/STATUSBAR-NetworkController_dual( 1069): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews set mobileLabel[SIM_0] =
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 set mobileLabel[SIM_1] =
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 GONE
,D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set : simMode = 0
,D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set as slot1`s
,E/SMD     (  233): DCD ON
,TIME-OUT KILL (timeout was 1800000ms),E/SMD     (  233): DCD ON
D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
D/AmoledAdjustTimer(  759): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
E/SMD     (  233): DCD ON
E/Watchdog(  759): !@Sync 64
D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
D/UiModeManager(  759): mCoverManager.getCoverState() : true
D/BatteryService(  759): stay LED for fully charged
D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1945): Disconnected process message: 10
D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
E/SMD     (  233): DCD ON
D/AndroidRuntime( 6206): 
D/AndroidRuntime( 6206): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6206): CheckJNI is OFF
D/AndroidRuntime( 6206): setted country_code = Poland
D/AndroidRuntime( 6206): setted countryiso_code = PL
D/AndroidRuntime( 6206): setted sales_code = XEO
D/AndroidRuntime( 6206): readGMSProperty: start
D/AndroidRuntime( 6206): readGMSProperty: already setted!!
D/AndroidRuntime( 6206): readGMSProperty: end
D/AndroidRuntime( 6206): addProductProperty: start
D/dalvikvm( 6206): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 6206): Added shared lib libjavacore.so 0x0
D/dalvikvm( 6206): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 6206): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 6206): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
E/memtrack( 6206): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 6206): failed to load memtrack module: -2
D/dalvikvm( 6206): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
D/AndroidRuntime( 6206): Calling main entry com.android.commands.pm.Pm
D/PackageManagerService(  759): deletePackageAsUser- pkg:com.test.thalitest, userId:0
D/PersonaManagerService(  759): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PersonaManagerService(  759): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService(  759): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager(  759): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager(  759): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManagerService(  759): deletePackage- pkg:com.test.thalitest, edmuserId:0
D/PackageManagerService(  759): deletePackage- pkg:com.test.thalitest, edmuserId:-1
D/ApplicationPolicy(  759): getApplicationUninstallationEnabled
D/ApplicationPolicy(  759): getApplicationUninstallationEnabled :  enabled true
D/PackageManagerService(  759): deletePackageX- pkg:com.test.thalitest, userId:0
D/PackageManager(  759): START PACKAGE DELETE: observer{1133476136}
D/PackageManager(  759): pkg{<packageName>}
D/PackageManager(  759): user{0}
D/PackageManager(  759): deletePackageAsUser : uid = 2000 userId = 0
D/PackageManager(  759): [MSG] DELETE_PACKAGE_AS_USER
D/PackageManager(  759): !@killApplicatoin: 10179, uninstall pkg
I/ActivityManager(  759): Killing 5151:com.test.thalitest/u0a179 (adj 1): stop com.test.thalitest
I/WindowState(  759): WIN DEATH: Window{4362a4f8 u0 com.test.thalitest/com.test.thalitest.MainActivity}
I/SurfaceFlinger(  242): id=16 Removed NainActivit (7/12)
I/SurfaceFlinger(  242): id=16 Removed NainActivit (-2/12)
I/SurfaceFlinger(  242): id=16 Removed NainActivit (-2/12)
D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
W/PackageSettings(  759): Skipping PackageSetting{427ba3c0 com.example.hello/10180} due to missing metadata
D/PackageManager(  759): Sending to user 0: act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000000 Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10179, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
D/dalvikvm( 1406): GC_EXPLICIT freed 4305K, 47% free 10030K/18744K, paused 5ms+4ms, total 65ms
I/FPMS_FingerprintManagerService( 1088): onReceive: android.intent.action.PACKAGE_REMOVED
D/AdaptiveEventManager( 1069): action=android.intent.action.PACKAGE_REMOVED
D/PackageManager(  759): Sending to user 0: act=android.intent.action.PACKAGE_FULLY_REMOVED dat=package:com.test.thalitest flg=0x4000000 Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10179, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
D/QuickConnect[1.1][2] ( 3311): SconnectManager.onReceiver - action : android.intent.action.PACKAGE_REMOVED, package : com.test.thalitest
I/InputReader(  759): Reconfiguring input devices.  changes=0x00000010
W/GeofencerStateMachine( 1220): Ignoring removeGeofence because network location is disabled.
I/PackageManager(  759):   Action: "android.intent.action.SENDTO"
I/PackageManager(  759):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  759):   Scheme: "sms"
D/dalvikvm( 1761): GC_EXPLICIT freed 876K, 35% free 12264K/18744K, paused 7ms+7ms, total 169ms
I/SELinux ( 6233): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6233):  
I/PackageManager(  759): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/dalvikvm( 2174): GC_EXPLICIT freed 987K, 42% free 10997K/18744K, paused 3ms+4ms, total 195ms
I/PackageManager(  759):   Action: "android.intent.action.SENDTO"
I/PackageManager(  759):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  759):   Scheme: "smsto"
D/dalvikvm(  759): GC_EXPLICIT freed 2708K, 57% free 23844K/54804K, paused 7ms+22ms, total 182ms
I/PackageManager(  759): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/SELinux ( 6233): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 6233):  
I/SELinux ( 6233):  
I/SELinux ( 6233): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 6233): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 6233): >>>>> Normal User
E/dalvikvm( 6233): >>>>> com.sec.esdk.elm [ userId:0 | appId:10094 ]
E/SELinux ( 6233): [DEBUG] seapp_context_lookup: seinfoCategory = platform
I/PackageManager(  759):   Action: "android.intent.action.SENDTO"
I/PackageManager(  759):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  759):   Scheme: "mms"
D/TimaKeyStoreProvider( 6233): in addTimaSignatureService
I/PackageManager(  759): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/TimaKeyStoreProvider( 6233): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 6233): Added TimaKesytore provider
I/PackageManager(  759):   Action: "android.intent.action.SENDTO"
I/PackageManager(  759):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  759):   Scheme: "mmsto"
D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
I/PackageManager(  759): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
D/RCPManagerService(  759): PackageReceiver onReceive()
I/PackageManager(  759):   Action: "android.intent.action.SENDTO"
I/PackageManager(  759):   Category: "android.intent.category.DEFAULT"
I/HarmonyEASService(  759): onReceive : android.intent.action.PACKAGE_REMOVED for 0
I/PackageManager(  759):   Scheme: "sms"
D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
D/EnterpriseDeviceManagerService(  759): Package has changed for user 0
D/EnterpriseDeviceManagerService(  759): Admin package name: com.google.android.gms
I/PackageManager(  759): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/SurfaceFlinger(  242): id=19 createSurf (1x1),2 flag=404, CatteryCove
I/PackageManager(  759):   Action: "android.intent.action.SENDTO"
I/PackageManager(  759):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  759):   Scheme: "smsto"
D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
I/PackageManager(  759): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager(  759):   Action: "android.intent.action.SENDTO"
I/PackageManager(  759):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  759):   Scheme: "mms"
I/PackageManager(  759): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
W/ActivityManager(  759): Permission Denial: getCurrentUser() from pid=6233, uid=10094 requires android.permission.INTERACT_ACROSS_USERS
I/PackageManager(  759):   Action: "android.intent.action.SENDTO"
I/PackageManager(  759):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  759):   Scheme: "mmsto"
I/PackageManager(  759): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
D/elm:14132( 6233): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
D/elm:14132( 6233): ELMEngine.ELMEngine( context ).
D/elm:14132( 6233): MDMBridge.setEnterpriseBridge()
D/elm:14132( 6233): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
W/Resources(  759): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/elm:14132( 6233): ElmAgentService : onCreate()
E/SMD     (  233): DCD ON
D/elm:14132( 6233): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
D/elm:14132( 6233): MainReceiver.listeningToPackageRemoved()
D/elm:14132( 6233): MDMBridge.getInstance()
D/elm:14132( 6233): MDMBridge.getAllLicenseInfoFromSDK()
D/elm:14132( 6233): MDMBridge.getAllLicenseInfoFromSDK()
I/SELinux ( 6246): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6246):  
D/elm:14132( 6233): MainReceiver.listeningToPackageRemoved(). SEND to KLMS. Remove All KNOX/ONS License
D/elm:14132( 6233): ElmAgentService : onDestroy().
I/ActivityManager(  759): Killing 5449:com.sec.android.soagent/u0a37 (adj 15): empty for 1815s
D/dalvikvm(  759): GC_EXPLICIT freed 958K, 57% free 23758K/54804K, paused 7ms+24ms, total 236ms
I/SELinux ( 6246): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 6246):  
I/SELinux ( 6246):  
I/SELinux ( 6246): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 6246): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/PackageManager(  759): delete sourFile : 
E/dalvikvm( 6246): >>>>> Normal User
E/dalvikvm( 6246): >>>>> com.sec.android.service.health [ userId:0 | appId:10016 ]
E/SELinux ( 6246): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/TimaKeyStoreProvider( 6246): in addTimaSignatureService
D/BackupManagerService(  759): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
V/BackupManagerService(  759): removePackageParticipantsLocked: uid=10179 #1
D/TimaKeyStoreProvider( 6246): Cannot add TimaSignature Service, License check Failed
W/Resources(  759): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ActivityThread( 6246): Added TimaKesytore provider
D/AndroidRuntime( 6206): Shutting down VM
D/PackageManager(  759): delete native library directory: 
D/PackageManager(  759): return delete result to caller: 1133476136
D/PackageManager(  759): returnCode: 1
D/dalvikvm( 6206): GC_CONCURRENT freed 96K, 14% free 670K/772K, paused 0ms+0ms, total 3ms
I/PackageManager(  759):   Action: "android.intent.action.SENDTO"
I/PackageManager(  759):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  759): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager(  759):   Scheme: "sms"
W/Resources(  759): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/PackageManager(  759):   Action: "android.intent.action.SENDTO"
I/PackageManager(  759):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  759):   Scheme: "smsto"
I/PackageManager(  759): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager(  759):   Action: "android.intent.action.SENDTO"
I/PackageManager(  759):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  759):   Scheme: "mms"
I/PackageManager(  759): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
W/Resources(  759): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/PackageManager(  759):   Action: "android.intent.action.SENDTO"
I/PackageManager(  759):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  759):   Scheme: "mmsto"
I/PackageManager(  759): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
W/ActivityManager(  759): Permission Denial: getCurrentUser() from pid=6246, uid=10016 requires android.permission.INTERACT_ACROSS_USERS
W/Resources(  759): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/dalvikvm( 6246): No JNI_OnLoad found in /system/lib/libsecure_storage_jni.so 0x425dfc28, skipping init
I/SecureStorage( 6246): [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
I/SecureStorage( 6246): [INFO]: SPID(0x00000000)This device supports Secure Storage
I/SecureStorage(  294): [INFO]: SPID(0x00000004)Credentials: uid 10016, gid 10016, pid 6246
I/SecureStorage(  294): [INFO]: SPID(0x00000004)Received function mask & code: 0000010C
I/SecureStorage( 6246): [INFO]: SPID(0x00000000)SS Daemon is running
I/SecureStorage( 6246): [INFO]: SPID(0x00000000)Processing data
W/Resources(  759): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/SecureStorage(  294): [INFO]: SPID(0x00000004)Credentials: uid 10016, gid 10016, pid 6246
I/SecureStorage(  294): [INFO]: SPID(0x00000004)Received function mask & code: 00000106
D/Launcher( 1264): onRestart, Launcher: 1114138400
D/Launcher( 1264): onStart, Launcher: 1114138400
D/Launcher.HomeView( 1264): onStart
D/SurfaceWidgetClient$ISurfaceWidgetStub( 1447): [237392/5] Surface widget visibility changed visibility = true on instance = 1
D/SurfaceWidget.Renderer( 1447): [237392/5] SurfaceWidget drawing first frame
W/Resources(  759): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/SurfaceFlinger(  242): id=20 createSurf (720x1280),1 flag=4, Mauncher
D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
W/Resources(  759): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  759): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  759): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  759): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
W/Resources(  759): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  759): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  759): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
W/Resources(  759): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  759): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  759): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
I/CrashAnrDetector(  759): onPackageRemoved : com.test.thalitest
D/UsbSettingsManager(  759): clearDefaults: com.test.thalitest
D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
D/InputReader(  759): Processing first event
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
